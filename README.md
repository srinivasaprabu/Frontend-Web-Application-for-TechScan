# Frontend-Web-Application-for-TechScan
TechScan is basically the source code version control info domain of Cast software. All the repos, users and their commits can be viewed in TechScan
Retrieve Data from 

-- TechScan Get repo API: 
	
	https://api.github.com/search/repositories?q='topic'

	Example: https://api.github.com/search/repositories?q=django

-- In the output JSON of the API call, you 'll get the Repo owner details.

-- Get Repo owner API:

	https://api.github.com/search/users?q='username'

	Example: https://api.github.com/search/users?q=akulakov
  
  Display the Programming Language Count and user repository detail
  
