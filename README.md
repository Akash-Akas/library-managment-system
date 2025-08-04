# library-managment-system

This is a library managment Api BAckend for the management of users and the books

# routes and the Endpoints

## /users
GET: get all the list of users in the systems
POST:create a new user

# /users/{id}
GET:get a user by id
PUT:updating a user by their ID
DELETE: deleting a user by their ID(check if the user still has an issued book) &&(is there any fine on user)

# /users/subscription-details/{id}
get:get a user subscription details by their ID
 >> Date of subscription
 >>valid till?
 >>fine if any?

# /books
GET:get all the books in the system
POST:add a new book to the system

## /books{id}
GET: get a book by its{id}
PUT:update a book by its id
DELETE:delete a book by its ID

#  /books/issued
GET: get all the issued books

# /books/issued/withFIne
GET:get all the issued books with their fine amount

### subsription types
>>Basic(3months)
>>standard(6months)
>>Premium(12months)

>>if a user missed the renewal date,then user should be collected with 100$
>>if a user mimsses his subscription,then user is expected to pay 100$
>>if user misses both renewal&subscription he will pay 200$


## commands:
npm init>> to start 
npm i express
npm i nodemon --save-dev

npm run dev
