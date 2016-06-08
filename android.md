# Coding Challenge
## The Task

Consider the following JSON to represent an Journey object.

 * `id`
 * `user_id`
 * `from` - latitude/longtitude for start point. Sample format: [ 40.4680577, -3.68662464 ]
 * `to` - latitude/longtitude for end point. Sample format: [ 40.4680577, -3.68662464 ]
 * `distance` - optimum meters travelled.
 * `duration` - optimum seconds the journey would have lasted.
 * `currency` 
 * `price` 
 * `discount` - discount to be applied.
 * `total_price` - the price minus any discounts
 * `created_at`
 
 Sample:
 ```json
 {
   "result":[
      {
         "id":"11",
         "user_id":"23",
         "from":[
            40.43862915039062,
            -3.717599868774414
         ],
         "to":[
            40.43637084960938,
            -3.685964584350586
         ],
         "distance":3000,
         "currency":"thb",
         "price":50.00,
         "discount":20.00,
         "total_price":30.00,
         "created_at":"2015-05-15T18:15:19Z"
      },
      {
         "id":"12",
         "user_id":"24",
         "from":[
            40.53862915039062,
            -3.717599868774414
         ],
         "to":[
            40.53637084960938,
            -3.685964584350586
         ],
         "distance":3005,
         "currency":"thb",
         "price":55.00,
         "discount":20.00,
         "total_price":35.00,
         "created_at":"2015-05-15T18:16:19Z"
      }
   ]
}
 ```
Design a UI view to display these information.


## Expectation:
- No need to focus on design a fancy UI. 
- Test familiarity on Android areas.
- Apply some design patterns or ensure coding standards.


## Bonus points (optional)
- Showing the array of journeys in a ListView.
- Showing some unit tests / UI tests.


Enjoy this coding challenge and all the best!
