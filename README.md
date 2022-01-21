// Creating Maven Project

1. mvn archetype:generate
groupId: com.BankingMicroservice
artifactId: BankingMicroservice

// Local and Remote repository initialization 

2. cd BankingMicroservice

3. git init

4. git status

5.  git add README.md

6.  git add .

7.  git commit -m "first commit: README.md and maven project added"

8.  git remote add origin git@github.com:Tristan-C01/BankingMicroservice.git

9.  git push origin master

// Creating and merging branches

10.  git branch dev1

11.  git branch dev2

12.  git checkout dev1

13.  echo "This is dev1's repository" >> dev1.txt

14.  git checkout dev2

15.  echo "This is dev2's repository" >> dev2.txt

16.  git checkout dev1

17.  git add .

18.  git commit -m "Commit for dev1"

19.  git checkout master

20.  git merge dev1

21.  git checkout dev2

22.  echo "This is dev2's repository" >> dev2.txt

23.  git add .

24.  git commit -m "Added dev2.txt"

25.  git checkout master

26.  git merge dev2

27.  git push origin master


