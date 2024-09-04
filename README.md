# jotreewater-site

This github page is for my personal website project. This project will use a ASP Dotnet Core implementation for a backend and a React frontend. One goal I have is to keep dependencies minimal.

The project's current status is *incomplete*

## Below is the plan for upcoming features:

### Phase 1:
1. Create a React frontend with the following features
	- Render a pdf of Joseph's current resume
	- Button for uploading a pdf
		- Prompt user for a password to update the document
	- Button for downloading a pdf 
2. Create a ASP dotnet Core backend with the following features
	- Service for handling upload requests
	- Service for handling download requests
	- Service for checking the given password
	- Model for saving the pdf metadata to a database
	- Database connection
	- Blob storage connection
3. Set up Azure to host the website
	- Set up the app service
	- Set up the PostgreSQL database
	- Set up the Azure blob storage
### Phase 2 Ideas:
- Proper Login Flow
- Implement a navbar
- Consider a kubernetes deployment over Azure's services
- Implement a blog page with editor and some CMS services
### Phase 3 Ideas:
- Greatly improve the security for Auth
- Improve aesthetics
- Create a wiki for recording what I learn