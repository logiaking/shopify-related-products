# shopify-related-products
A product loop using metafields in Shopify, with add to cart button &amp; quantity


This loop utilises metafields to output the product handle and uses it to fetch information on chosen products.

This is using "Advanced Custom Fields" for Shopify - the custom field used is the Reference Type "Product".

The custom field details are -

Namespace: related
Key: related_products
Label: Related Products

This was set up as a repeatable field that outputs a JSON string e.g - ["product-1", "product-2"] where product is the product handle.



