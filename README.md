# **Critics RC**

After being working on the Critics app for some weeks, it is time to create a Release Candidate that merges all the pieces together. The ERD has changed just a little. The User model has been simplified and a cover image has been added to the Game and Company models:

![database models](https://p-vvf5mjm.t4.n0.cdn.getcloudapp.com/items/YEuOpYbw/bc1aeefc-9e8c-4320-bcd9-579627abc982.jpg?source=viewer&v=642d09bf6730232b790c7723248c900f)

Find the design [**here**](https://www.figma.com/file/d5h7aouzicyQWlYGn1cIsd/C4-Critics-Beta?node-id=888%3A708). It includes views for almost all the CRUD operations for all the entities. The CRUD operations not included should be performed on the rails console. For example, updating the role of a user or creating Platforms and Genres should be done on rails console. (or through the seed file)

![critics preview](https://p-vvf5mjm.t4.n0.cdn.getcloudapp.com/items/GGupo97b/75084c60-87ec-47ce-b5a6-7f69e86660d8.png?source=viewer&v=f7a60c217c1290309f28680ac36d5231)

## **Main objective: Build the project Release Candidate (RC)**

Using Rails and the MVC pattern, build all the models, controllers, and views necessary to bring to life the app designs.

- Your app should include authentication (with Devise and Omniauth) and authorization (with Pundit).
- The cover images should be stored using Rails ActiveStorage.
- Use the associations and validations described in the previous daily assignments.