# Create with Express

Build the **router** and the **createOne** controller for the Books and Pets database.

## Setup

1. Fork this repository
2. Clone the forked repository onto your local machines
3. In the root directory, type `npm install`, which installs dependencies for the project

You have some additional steps to do to setup this exercise:

4. In ElephantSQL, create a new instance

![](images/elephaphantSQLInstance.png)

5. Copy the URL of your new instance

6. Create the file `.env` in the root directory It should contain a single line, which specifies the url from the instance createed above, e.g (where the starts will contain your password):

```env
PGURL = "postgres://zzlrlrtu:****@tyke.db.elephantsql.com/zzlrlrtu" 
```

Finally:

7. type `npm start`, which starts a development server that will reload whenever you make any changes to source files. All being well, you will have a terminal window that looks like the following:

![](images/terminal.png)

## Instructions

- Build the `router` for the Books resource
- Build the `router` for the Pets resource
- Build the `createOne` controller for the Books resource
- Build the `createOne` controller for the Pets resource

## Tips

- Take a look inside the `model` to see what data types you are working with.
- Use ElephantSQL to check if your requests are succesfully creating rows in the database (there will be mockData stored in there already).

## Extra Challenge 1

- Add validation in your controller that sends a useful message back to the client when there's an error, with suggestions as to what they could do differently.

## Extra Challenge 2

- Have a look inside `utils/mockData.js` and see if you can generate some mock data and build your own resource and model ie. a bank account resource or a vehicle tax resource. Take a look at [faker.js](https://github.com/Marak/Faker.js) for inspiration.
