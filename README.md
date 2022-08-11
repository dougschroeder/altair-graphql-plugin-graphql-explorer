# altair-graphql-plugin-graphql-explorer

A Plugin for [Altair GraphQL Client](https://altair.sirmuel.design/) (only tested on [Chrome extension](https://chrome.google.com/webstore/detail/altair-graphql-client/flnheeellpciglgpaodhkhmapeljopja?hl=en)) that adds the [OneGraph GraphiQL Explorer](https://github.com/OneGraph/graphiql-explorer)

# Install

```
npm install
```

# Build and Run

```
npm run build; npm run web-server
```

# Install Altair GraphQL Client Chrome Extension

https://chrome.google.com/webstore/detail/altair-graphql-client/flnheeellpciglgpaodhkhmapeljopja?hl=en

# Read about Altair Plugins

https://altair.sirmuel.design/docs/plugins/

# Modify Altair Settings to point to locally served plugin
In the Altair Chrome extension, go to settings, click the "toggle advanced mode" link, add set this JSON:

```
{
  "theme": "system",
  "language": "en-US",
  "addQueryDepthLimit": 3,
  "tabSize": 2,
  "enableExperimental": true,
  "plugin.list": [
    "url:altair-graphql-plugin-graphql-explorer::[url]->[http://localhost:8002]"
  ]
}

<img width="800" alt="image" src="https://user-images.githubusercontent.com/5340632/184222817-37abb99a-b37b-4da3-b34e-ffde82a341f1.png">

```

# Restart Chrome Browser Extension

# Click on the "GraphiQL Explorer" tab

<img width="179" alt="image" src="https://user-images.githubusercontent.com/5340632/172533096-da15d9f5-447a-42f7-81b1-4cb41c551954.png">

# Start Exploring!
