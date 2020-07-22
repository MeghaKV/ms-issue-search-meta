# SPFX issue mentioned in https://github.com/SharePoint/sp-dev-docs/issues/5860

## Steps to reproduce: 
1. Deploy the version-1 package and add application
2. Create a `search` webpart and save the page
3. Deploy the version-2 webpart and view the above page.
4. Expected result: web part should show the rich text HTML, but after you will get empty content.
5. `{isHtmlString:true}` in the property meta empties the property.