# docusaurus-plugin-hotjar

A docusaurus plugin to integrate Hotjar.

## Usage

1. Copy the `src/index.js` file to a folder in your docusaurus install. For example `plugins/docusaurus-plugin-hotjar`.
1. Add plug in `docusaurus.config.js`:

   Example:

   ```js
   module.exports = {
     plugins: [
       // ...
       path.resolve(__dirname, 'plugins/docusaurus-plugin-hotjar')
     ]
   }
   ```

1. Add the `hotjar > siteId` property to your `themeConfig`:

   Example:

   ```js
   module.exports = {
      themeConfig: {
        hotjar: {
          siteId: '225871893',
        }
      }
    }
    ```
