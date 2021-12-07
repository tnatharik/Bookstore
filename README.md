# Bookstore

	1. Install IntellJ Community
	2. Install MongoDB local or use yaml to run mongo on docker
	3. Use Mongo DB compass to check
	4. Use spring boot https://start.spring.io/ to download the initializer
	5. Create the Book App, Book, BookRepo, Book Controller and Book Service
	6. Book data model class corresponds to entity and table book
	7. BookRepo is an interface that extends MongoRepository for CRUD methods and custom finder methods. It will be autowired in BookController
	8. BookController is a RestController which has request mapping methods for RESTful requests such as: getAllBook, createBook, updateBook, deleteBook, findByPublished
	9. Configuration for Spring Data MongoDB is in application.properties.
	10. pom.xml contains dependencies for Spring Boot Web MVC and Spring Data MongoDB.
	11. Resources
		a. https://www.bezkoder.com/spring-boot-mongodb-crud/
		b. https://www.bezkoder.com/spring-boot-vue-mongodb/
		c. Spring Boot Tutorial - Build a Rest Api with MongoDB

	• Steps to Run Vue
	• Open Ubuntu 20.04 LTS
	• Run
		○ npm install vue
		○ sudo npm install -g @vue/cli
		○ vue --version
		○ vue create newbookstores
		○ 2.x
		? Please pick a preset: Manually select features
		? Check the features needed for your project: Choose Vue version, Babel
		? Choose a version of Vue.js that you want to start the project with 2.x
		? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files
		? Save this as a preset for future projects? No
		○ cd newbookstores
		○ npm run serve

