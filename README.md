#!/bin/bash


echo "# whz-host-maintain-app" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/virtualadrian/whz-host-maintain-app.git
git push -u origin master
