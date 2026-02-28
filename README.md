# Webbackend HW1 - Book API

## PUT - Update Book
Endpoint:
PUT /api/books/{id}

![PUT Screenshot](PUT_Screenshot.png)

## PATCH - Partial Update
Endpoint:
PATCH /api/books/{id}

![PATCH Screenshot](PATCH_Screenshot.png)

## DELETE - Remove Book
Endpoint:
DELETE /api/books/{id}

![DELETE Screenshot](DELETE_Screenshot.png)

Using GET to show deleted book

![DELETE2 Screenshot](Delete2_Screenshot.png)


## Pagination
Endpoint:
GET /api/books/paged?page=0&size=1

![Pagination Screenshot](GETPag_Screenshot.png)

## Advanced Endpoint
Endpoint:
GET /api/books/advanced?title=java&minPrice=25&sortBy=price&order=desc&page=0&size=2

![Advanced Screenshot](AdvancedPAG_Screenshot.png)
