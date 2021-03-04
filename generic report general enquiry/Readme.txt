Import sequence:
1. classification: don't use parameter tree/defs so that process definition will imported as well
ex: ./ClassificationTree.ksh import \path_of_your_file\classification_general_enquiry_emp_config.xml replace Admin Admin standard genon 
2. event mapping
ex: ./Eventmappings.ksh import \path_of_your_file\event_mappings_general_enquiry_emp_config.xml replace Admin Admin
3. change url in eForm Definition, adjust to your system url
4. upload VOF and Adapter
5. place the js and css on the resource folder.
ex: \installation_directory\tomcat\webapps\css
	\installation_directory\tomcat\webapps\js
6. adjust the style resource of general enquiry form:
	- open general_enquiry form
	- move to resources tab
	- adjust or add the js or css (ex: https://yourcouncilurl.com/laganresources/css/gov.0.3.css) 