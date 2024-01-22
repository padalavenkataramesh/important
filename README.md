
**Tools**
1) 
Remove UnUsed Assets/ Files using Deadfiles npm package
**URL**: https://www.npmjs.com/package/deadfile
**Package**: npm i deadfile
deadfiles run the command to track prokect dead files **npx deadfile index.js --dir C:\project\src  --output report.json** 

2) 
**URL**: https://www.npmjs.com/package/cloc
**Package**: npm i cloc
Windows: install package & PERL also required to run  - npx cloc [options]
Ubuntu
> cloc src --by-file

Result: 
 190 text files.
     190 unique files.                                          
       1 file ignored.
       File                                                                         blank        comment           code
----------------------------------------------------------------------------------------------------------------------
src/lang.ts                                                                          59             13             864
src/component/index.tsx                                                              28             28             699

