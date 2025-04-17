Reference [link](https://mui.com/material-ui/)

Installation guide [link](https://mui.com/material-ui/getting-started/installation/)

Command to add support:
```
npm install @mui/material @emotion/react @emotion/styled
npm install @fontsource/roboto
npm install @mui/icons-material
```



### Error

```
npm install @mui/material @emotion/react @emotion/styled


npm error code EACCES
npm error syscall open
npm error path /Users/ardanish/.npm/_cacache/index-v5/c7/5a/eaa53dfae9b2e34d7547dcfe77dca6246dac33882ad24cae8d4010d1575c
npm error errno EACCES
npm error
npm error Your cache folder contains root-owned files, due to a bug in
npm error previous versions of npm which has since been addressed.
npm error
npm error To permanently fix this problem, please run:
npm error   sudo chown -R 501:20 "/Users/ardanish/.npm"
npm error A complete log of this run can be found in: /Users/ardanish/.npm/_logs/2025-04-17T07_50_08_017Z-debug-0.log
ardanish@helloardanish mediai % 



## After running : sudo chown -R 501:20 "/Users/ardanish/.npm" and then 

ardanish@helloardanish mediai % npm install @mui/material @emotion/react @emotion/styled

added 61 packages, and audited 366 packages in 8s

135 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
ardanish@helloardanish mediai % 


## Adding robot font

ardanish@helloardanish mediai % npm install @fontsource/roboto

added 1 package, and audited 367 packages in 6s

136 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
ardanish@helloardanish mediai % 




## Adding icon support

ardanish@helloardanish mediai % npm install @mui/icons-material

added 1 package, and audited 368 packages in 5s

137 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
ardanish@helloardanish mediai % 


```
