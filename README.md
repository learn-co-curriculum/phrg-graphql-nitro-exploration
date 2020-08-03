# Exploring Nitro via GraphQL

This lab is a group activity. Before you start, acquire your group and your Nitro environment URL from the instructor.

Using the GraphQL Documentation Explorer, answer the following questions and complete the challenges.

## Querying Data

- What are the names of all the `BusinessUnit`s stored in your demo environment?

- What is the name of the `ConnectRoom` with an id of 138?

- Find and write a query that will display all `windowOptions` and `sidingOptions`.

- Query for category names for all learningDojoCourses, with each course's title and description.

- Go through the fields on a `JobPosting`. Which fields are Scalar types and which ones are objects?

- Go through the fields on a `StockItem`. What are the non-nullable fields? Which fields are Scalar types? What fields return objects, and what are those objects?

## Mutating Data

- Create an active `Company` called `<your name> test company`.

- Update the company you just created to `Champion <your name> test company` and deactivate it.

- Create a new `InstallationCrew`. Make up every "attribute" that is necessary, but do not add any fields that are not necessary. What are all the `InstallationCrew` required fields?

- Update the installation crew you just created with for the state of `"WI"`, city of `"Madison"`, and `contactName` of `"Clark Kent"`.
