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
