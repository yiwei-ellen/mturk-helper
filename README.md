# mturk-helper
Package for supporting recruitment and payment of participants in multiplayer experiments
### scripts
`code` npm run dev
* this allows seeing the effect of local changes to files in /public folder
`code` npm run build
* this cleans all js files in the /public folder and compiles from TS, source maps excluded
`code` npm run test
* this runs tests in src/_test_
### setup
1. install editorconfig as an extension in VSCode
2. the .editorconfig file sets the formats for coding
3. create a config.json in stc/ts folder and fill in the content as follows
```
{
    "access_key": "YOUR_AWS_ACCESS_KEY",
    "secret_key": "YOUR_AWS_SECRET_KEY"
}
```