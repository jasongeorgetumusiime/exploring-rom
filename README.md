### Exploring Ruby Object Model

A simple demostration of using Ruby Object Model to build Database Applications. An application is layered as such
- Relations: Responsible for implementing database queries
- Repository: Provide a bridge between your application's business layer to the persistent layer. Resposible for providing and saving materialized objects from and to the database respectively
- Model: Responsible for representing the data models in your applcation. This is where the business logic of the application is implemented
