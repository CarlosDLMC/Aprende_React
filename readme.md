Before installing any npm library you have to run this on the background:

C:\"Program Files"\SourceForge\cntlm-0.92.3\cntlm.exe -c .\cntlm_example_conf.ini -v -f 

For the packages:
Node is much easier in that respect than python.

npm init
will create a new package.json. From then on any npm modules you install will default to the local node_modules folder in the directory you created the package.json in.

Create a new project: npm create vite@latest tornado -- --template react