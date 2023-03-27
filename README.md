# Nettbil Demo

This demo includes a simple web to lead form that creates a lead in Salesforce.

- Web to Lead form hosted on visualforce page
- A custom guided lead path
- A custom guided opportunity path.
- Car object to hold make, model, year, and price etc.

## Hands-on demo in Salesforce org

Note: The deployment site requieres that this repo is public under deployment. Remember to make it private again after the demo.

You can quickly spin up an org by clicking on the picture below. \
This will create a scratch org that you have access to for 1 day \
[![Demo scratch org](/.assets/deployDemo.png)](https://hosted-scratch.herokuapp.com/launch?template=https://github.com/ehsky/Nettbil-demo)

# Demo content

## Contact form

The contact form is hosted on a visualforce page and is a copy of the website https://www.nettbil.no/no-information-found with a few changes to the form. \
The website can be accessed by adding `/apex/ContactForm` to the end of the scratch org url. \
![Contact form](/.assets/contactForm.png)

## Guided lead path

In the Sales Console. The guided lead path is a custom path that is shown when a lead is created. \
![Guided lead path](/.assets/lead.png)

## Guided opportunity path

In the Sales Console. The guided opportunity path is a custom path that is shown when an opportunity is created. \
![Guided opportunity path](/.assets/opportunity.png)
