# Test task for the applicant for the position of frontend developer

User Data [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)

Link to layout [https://www.figma.com/file/X8Ke95Xuc9ZXrZJ3DzQjOW/Test-task?node-id=2%3A2](https://www.figma.com/file/X8Ke95Xuc9ZXrZJ3DzQjOW/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5?node-id=0%3A1)

## It is necessary to implement the proposed layout, and write a simple SPA in React 16 using the following tools, technologies and approaches:

- Component use of CSS
- Implement SPA using TypeScript
- scss preprocessor
- Block reuse
- Splitting the code into React components (presentational and container components)
- webpack

**We are waiting for your link to Github with this test task.**


💡 Try to write modular, isolated, reusable code.

### **The layout task looks like this:**

It is necessary to make up two pages “List of users” and “User profile”
#### A list of users:

1.     Display 10 users according to the layout. Get data from [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)
2.     While the list of users is being loaded, there should be a loading indicator (any design at the discretion of the artist)
3.     Withdraw to the card:
	- name
	- address. city
	- company.name
4. The “Details” button should lead to the “User Profile”
5. Implement list filtering based on Name and City in alphabetical order

#### User profile:
1. Display in the profile:
	- name
	- username
	- email
	- address.street
	- address. city
	- address.zipcode
	- phone
	- website

2. All form fields except Comment must be prefilled from [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)
3. Implement the edit button, initially the fields must be readonly, after clicking on the button, the fields can be edited
4. Implement validation on the client
5. All form fields, except for the Comment field, are required
6. From the form data when submitting, you need to generate JSON and output it to console.