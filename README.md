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
######setting up webstorm
set configuration->add testing dict /test

#####
######Member application 2
using lodash _.extend to extend local variables from args.  
output html:
```
mocha --reporter doc 
```