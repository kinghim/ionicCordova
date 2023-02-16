# ionicCordova

- https://ionic.io/docs/appflow/tutorial/start
- npm install -g @ionic/cli native-run cordova-res
- ionic start --cordova ionicCordova blank --type=angular


# initial push
- git config --global user.email "yourEmail@hotmail.com"
- git config --global user.name "kinghim"
- git add .
- git commit -m "initial"
- git push --set-upstream https://github.com/kinghim/ionicCordova.git master


# routine pull commit push
- git checkout master 
- git fetch 
- git pull 
- git add . 
- git commit -m "message" 
- git push --set-upstream https://github.com/kinghim/ionicCordova.git master 


# add multiple git repos
- git remote add main https://gitlab.com/other-git/other.git
- git fetch main
- git push main


# remove commit
- git reset --hard HEAD~1
- git push -f
