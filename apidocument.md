////page1
1.api for categories
http://localhost:8900/category

///page2
1.products
http://localhost:8900/products

2.products wrt categories
http://localhost:8900/products?category_id=2

filters

3.api for cost filer
http://localhost:8900/filter/1?lcost=200&hcost=500

4.pagination
http://localhost:8900/filter/1?lcost=100&hcost=1000&skip=0&limit=2

5.sort
    sort low to high 
    http://localhost:8900/filter/2?lcost=100&hcost=1000&sort=1

    sort high to low 
    http://localhost:8900/filter/2?lcost=100&hcost=1000&sort=-1

///page3

1.details about products
http://localhost:8900/productDetails/1

2.menu of categories
http://localhost:8900/menu/1


///page4(post)
1.menu items on user selection
localhost:8900/menuItem
 body[3,5,7]


2.api to place order
localhost:8900/placeorder

3.delete order
localhost:8900/deleteorder

4.update order
localhost:8900/updateorder/6203c2fb48aa24fa0dc3cfee?status=success

///page5

1.list orders
http://localhost:8900/orders
http://localhost:8900/orders?email="snigdhabommareddy@gmail.com"