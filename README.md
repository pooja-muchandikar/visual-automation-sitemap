# Visual Automation with BackstopJS
A script to conduct visual testing with [BackstopJS](https://github.com/garris/BackstopJS). 

### Sitemap XML Feature 
Steps to set up the Sitemap XML feature with Visual Automation:
1. Create a `.env` file and add the `baseUrl` and the `referenceUrl` to this file.
2. Run `npm install` command
3. Create reference screenshot from reference site (For expected results) `npm run reference:xml`
4. Run the test(It will take the screenshot of the given site and will test against reference screenshot) `npm run test:xml`
s