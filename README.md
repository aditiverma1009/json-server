use `npm run jsonserver`

Link: `https://www.youtube.com/watch?v=1zkgdLZEdwM`

Can use filters and sorts too:
- GET SINGLE COMPANY http://localhost:3000/companies/1 
- GET ALL USERS OF A COMPANY http://localhost:3000/companies/1/users 
- FILTER COMPANIES BY NAME http://localhost:3000/companies?name=Microsoft http://localhost:3000/companies?name=Microsoft&name=Apple 
- PAGINATION & LIMIT http://localhost:3000/companies?_page=1&_limit=2 
- SORTING http://localhost:3000/companies?_sort=name&_order=asc 
- USERS AGE RANGE http://localhost:3000/users?age_gte=30 http://localhost:3000/users?age_gte=30&age_lte=40 
- FULL TEXT SEARCH http://localhost:3000/users?q=Paul

Can also implement get, post, patch, delete..