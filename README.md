### [Data Model, Entities, and Relationships](https://cocoacasts.com/data-model-entities-and-relationships/)

#### Author: Bart Jacobs

Core Data is great at managing relationships. In this tutorial, we continue our exploration of the data model by taking a close look at relationships.

## Project Setup

Open Xcode and create a new project based on the **Single View Application** template. Don't forget to check **Use Core Data** during project setup.

![Setting Up the Project](https://cocoacasts.s3.amazonaws.com/data-model-entities-and-relationships/figure-project-setup-1.jpg)

Before we can start working with relationships, we need to add a few entities to the data model. Open **Library.xcdatamodeld** and add three entities, **Library**, **Author**, and **Book**.

The **Library** entity has two attributes, **name** and **location**, both of type **String**. The **Author** entity also has two attributes, **firstName** and **lastName**, both of type **String**. The **Book** entity has three attributes, **title** of type **String**, **publicationDate** of type **Date**, and **pages** of type **Integer 16**. This is what the data model should look like in the data model graph.

![Populating the Data Model](https://cocoacasts.s3.amazonaws.com/data-model-entities-and-relationships/figure-data-model-1.jpg)

**Read this article on [Cocoacasts](https://cocoacasts.com/data-model-entities-and-relationships/)**.
