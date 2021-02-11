# shopify_bundles
The code here helps to create a bundle list section on product page for your Shopify store

Copy the following code to product-template.liquid (normally to the end of the file, but it depends on where you want to display the bundles).
`bundle_list_title` is the title of the bundle list section and `columns` is how many bundle products per row in the section on desktop view (default to 1 for mobile view).

```
{% include 'product-bundle-collection', bundle_list_title: 'Choose a bundle that works best for you', columns: 3 %}

```

