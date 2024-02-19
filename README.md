# OnlineContactManagementSystem
1. Created H2 Database to store the data
2. Created endpoints such as
	POST /api/v1/users – adding contact details
	GET /api/v1/users/{id} – getting contact details by userId
	PUT /api/v1/users/{id} – updating contact details by userId if it already exists
	DELETE /api/v1/users/{id} – deleting contact details by userId
3. Created Log info when contact details is created and modified using AOP
4. Tested the api on vscode using ThunderClient.
