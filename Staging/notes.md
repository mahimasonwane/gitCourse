
staging
git status
👉 Definition:
Ye command batati hai ki kaun si files modified, staged ya untracked hain.

git add filename
👉 Definition:
Ye command file ko staging area me bhejti hai (commit ke liye ready karti hai).

git add .
👉 Definition:
Saari changed files ko ek saath staging area me add karta hai.

git diff
👉 Definition:
Working directory aur last commit ke beech ka difference dikhata hai (unstaged changes).

git diff --staged
Staging area me jo files hain unke changes dikhata hai.
git commit -m "message"

👉 Definition:
Staged files ko final repository me save karta hai (permanent snapshot banata hai).

git restore --staged filename
👉 Definition:
Staged file ko wapas unstaged karta hai (commit se hata deta hai, file delete nahi hoti).

git restore --staged .
👉 Definition:
Saari staged files ko unstaged kar deta hai.

git reset HEAD filename
👉 Definition:
File ko staging se hata kar working area me wapas bhej deta hai (unstage).