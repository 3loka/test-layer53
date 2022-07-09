
## Why should you use this Layer?
You can spin up your own Express(Node.js) website in seconds. Deployment happens on an Azure App Service.

Note: Once you create a repo out of this layer, you can find your website deployed at <azure_app_name>.azurewebsites.net.

## What are the inputs to pass while setting up the layer?
```
# Name of the Azure App which has been configured to host the website
- AZURE_APP_NAME

```

#### Github apps installed with this stack
```Github App for Azure```

## How to setup local development server?
```
# to start a local development environment, and view in browser.
npm install
npm start
open http://localhost:3000 

# to run tests
npm test

# to generate a production build
npm build
```

## Learn more 

### ExpressJS
Visit [Expressjs.com](https://expressjs.com) to view the full documentation.

### Azure Cloud
Learn more about [Azure](https://docs.microsoft.com/en-us/azure) from the official site.


## Other Useful links

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Trilok Ramakrishna ([@3loka](https://twitter.com/3loka))
