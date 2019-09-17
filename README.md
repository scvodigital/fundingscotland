# IMPORTANT DEPLOYMENT STEPS

If you make any changes to `site-configurations.json`, once they have been pushed you need to do the following
* Go into the `emailer` project
* Run `npm i --save-dev https://github.com/scvodigital/fundingscotland.git`
* Push those changes to `emailer#development`
* Run `npm run deploy`

This is to ensure that the emailer is aware of any changes to site configurations