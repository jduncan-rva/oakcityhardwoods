---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

# meta description
description : "Lorem ipsum dolor sit amet"

# product Price
price: "20.00"
priceBefore: "25.00"

# Product Short Description
shortDescription: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut"

#product ID
productID: "1"

# type must be "products"
type: "products"

# product Images
# first image will be shown in the product page
images:
  - image: "images/products/product-2.png"
  - image: "images/products/product-1.png"
  - image: "images/products/product-3.png"
  - image: "images/products/product-4.png"
---

