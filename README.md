Personal Website 
====
Template from [al-folio](https://github.com/alshedivat/al-folio). 

Tips:
Change stuff

Go to vs

Change config well

Add your files

Maybe disbable imagemagick

Inside gem file, add on first line
```
gem ‘wdm’, ‘>=0.1.0’
```
Add and comment

Now kind of difficult, but need to have ```rbenv``` and a nice version of Ruby installed (I use 3.2.2). Likely, it will not be activated, but it suffices to call:
```
export PATH="$HOME/.rbenv/shims:$PATH"
rbenv local 3.2.2
```
to be able to work with the other commands
Run on terminal:
```
bundle install 
bundle exec jekyll serve 
```
Copy server address and paste into browser
Check change
Once finished commit
once finished, before deploying: 
- push to master in a new terminal, 
- clone again the project from master,
- then do the same commands until you are just before calling bundle exec
- now call deploy. this time you do not push! 
Call
```
git add .
git commit -m "message"
bin/deploy —user 
```
Now the master will have the right version. 

