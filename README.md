# main_submodule
testing git submodule workflow<br/></br>

https://chrisjean.com/git-submodules-adding-using-removing-and-updating/<br/></br>

after cloning main, to clone submodule do:<br/>
git submodule update --init -- sites/a.example.com
<br/></br>
then cd to sites/a.example.com and do:<br/>
git checkout master
<br/><br/>
to pull submodule updates:<br/>
git submodule update --recursive --remote (gets head detached)<br/>
git submodule foreach git pull origin master (stays in master branch)
