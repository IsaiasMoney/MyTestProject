# MyTestPro

    export GIT_COMMITTER_EMAIL="$CORRECT_EMAIL"
fi

if [ "$GIT_AUTHOR_EMAIL" = "$OLD_EMAIL" ]
then
    export GIT_AUTHOR_NAME="$CORRECT_NAME"
    export GIT_AUTHOR_EMAIL="$CORRECT_EMAIL"
fi
' --tag-name-filter cat -- --branches --tags


…or create a new repository on the command line
echo "# leetcode" >> README.md

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/IsaiasMoney/leetcode.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/IsaiasMoney/leetcode.git
git branch -M main
git push -u origin main
