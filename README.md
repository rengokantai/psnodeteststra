####psnodeteststra
#####intro
######installation
```
npm init
```
set:
```
test command:node node_modules/mocha/bin/mocha
```

######optional installations
put mocha.opts file in test folder,edit
```
--compilers coffee:coffee-script/register
--reporter spec
```
to recog coffeecript