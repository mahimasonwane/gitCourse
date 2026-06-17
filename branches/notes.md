
1. git branch //checkout branch
2. git branch featureBranch //create branch 
3. echo master branch> newFileMaster.txt
4. git add. // add files
5. git commit -m "initial commit"
6. git log  // history of commits
7. git checkout <branchname>
8. echo feature branch -> newFilefeaturebranch.txt
    
    |
    git add.                      // add files
    git commit -m "initial commit"
    git log                      // history of commits
   

   i.git branch (display avaiable branch)
   ii.git branch <branchname>  (create new branch)
   iii. git checkout <branchname> switch to a diffrent branch
 

 git branch
👉 Kaam:
available branches list karta hai
kaunsi branch active hai wo * se dikhata hai
Example:
* master
  featureBranch

  2. git branch featureBranch (create)
git branch featureBranch
👉 Kaam:
new branch banata hai
BUT tum usme switch nahi hote

📌 Important:
👉 Ye sirf COPY banata hai current state ka
master me file banana
echo master branch > newFileMaster.txt

4. git add .
👉 Kaam:
changes ko staging area me bhejta hai
📌 Simple meaning:
👉 “Git, isko commit ke liye ready kar do”5. git commit

5. git commit -m "initial commit"
👉 Kaam:
snapshot save ho gaya
history me record ban gaya
📌 Master branch ab safe ho gaya

6. git log
git log

👉 Kaam:

commit history dikhata hai

📌 Tumhe milega:

commit id
message
date

7. git checkout <branchname>
git checkout featureBranch
👉 Kaam:
branch switch karta hai
📌 Meaning:
👉 “ab main master se nikal ke featureBranch me chala gaya”

8. feature branch me file banana
echo feature branch > newFilefeaturebranch.txt
👉 Kaam:
ab ye file sirf featureBranch me bani

💡 SUPER SIMPLE ONE-LINE MEMORY
branch → list/create
checkout → switch
add → stage
commit → save snapshot
log → history