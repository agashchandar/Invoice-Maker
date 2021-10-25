# Create an Invoicing Application with Python and Bootstrap5
A simple project on creating an invoicing application from scratch using Python Django and Bootstrap framework to create the front-end.

## Client Journey for the Invoicing App with Django
-The client is usually the focus of many app development planning sessions and development brainstorming sessions. We need to understand the end-user of the application, what they are trying to achieve and what problem they are trying to solve.

-In essence, our clients are looking for an affordable way to create invoices online, print them out or email them to a client. They would also like to record their invoices in one place, keep track of the total sum they have invoiced, per client and in general. The client also wants the ability to search for invoices, track for payments and even send reminders if they have not received payments.

-These client needs form a basis for the features of our apps, understanding the client needs allows us to better design our Django app.

## Main Features
-Creating a PDF document from django (useful for dashboard, SaaS web app development)

-Building a dashboard application - Crud development with Django (creating, reading, updating and deleting records) 

-The invoice model will have things like: invoice number, payment status, payment instructions, client information and product information.

-Client information — is a class in itself, you need to provide name, address details, contacts for the client. It is also re-usable as you can have multiple invoices for the same client. It then makes sense, the client should be a model. This will however be a “slave” model to the invoice class.

-Similarly the product/services models can be related to the invoice model. In the product/services models we can describe the specific products and services we are offering that we will be charging for.

## Screenshots
![Client Journey](https://github.com/agashchandar/Invoice-Maker/images/invoice-1.PNG)
![Design Journey](https://github.com/agashchandar/Invoice-Maker/images/invoice-2.PNG)
![Model Class Design](https://github.com/agashchandar/Invoice-Maker/images/invoice-3.PNG)
![Login](https://github.com/agashchandar/Invoice-Maker/images/invoice-4.PNG)
![Invoice Dashboard](https://github.com/agashchandar/Invoice-Maker/images/invoice-5.PNG)
![Invoice PDF](https://github.com/agashchandar/Invoice-Maker/images/invoice-6.PNG)

