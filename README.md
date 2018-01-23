$ ng serve
Your global Angular CLI version (1.6.4) is greater than your local
version (1.5.0). The local Angular CLI version is used.

To disable this warning use "ng set --global warnings.versionMismatch=false".
module.js:491
    throw err;
    ^

Error: Cannot find module '@angular-devkit/core'
    at Function.Module._resolveFilename (module.js:489:15)


very simple answer the below command to resolve the problem

npm install --save-dev @angular/cli@latest