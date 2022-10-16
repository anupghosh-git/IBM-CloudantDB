# IBM-CloudantDB
- Query:
  - Select all data form the table
    - {
       "selector": {}
      }
  - searching by _id(promary key)
    - {
   "selector": {
      "_id": {
         "$gt": "4"
      }
   }
}
  - Restirct the fields to show
  -   - {
   "selector": {},
   "fields": [
      "_id",
      "price",
      "square_feet"
   ]
}
  - select restricted fileds and query by _id
    - {
   "selector": {
   "_id": {
         "$lt": "4"
      }
   },
   "fields": [
      "_id",
      "price",
      "square_feet"
   ]
}
