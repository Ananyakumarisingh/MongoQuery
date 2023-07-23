# Opperators

1. __<=__  -  lte (less than equal to)  -  db.`collectionName`.find( { age: { $lte: 50 } } )

2. __>=__  -  gte (gess than equal to)  -  db.`collectionName`.find( { age: { $gte: 50 } } )

3. __<__  -  lt (less than)  -  db.`collectionName`.find( { age: { $lt: 50 } } )

4. __>__  -  gt (gess than)  -  db.`collectionName`.find( { age: { $gt: 50 } } )

5. __==__  -  eq (equal to)  -  db.`collectionName`.find( { age: { $eq: 50 } } )
or, db.`collectionName`.find( { age: { $eq: 50 } } )

6. __!=__  -  ne (not equal to)  -  db.`collectionName`.find( { age: : 50 } )

7. __&&__  -  And (and)  -  db.`collectionName`.find( { $and: [ { age: { $eq: 50 } }, { height: { $eq: 6'5 } } ] } )

8. __||__  -  Or (or)  -  db.`collectionName`.find( { $or: [ { age: { $eq: 50 } }, { height: { $eq: 6'5 } } ] } )

9. 


10. 


11. 