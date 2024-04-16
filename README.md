**System Asset Inventory reporting**

The CISO of an enterprise wants to understand his organization's system inventory.  A data repository has been created at https://github.com/k2-mivs/Asset_reporting_sample for reporting. 

There are two sample data files - one representing asset inventory and the other representing a list of system boundaries.

	1. The asset inventory file has an ID field that has the Org and the System ID in one field. 
 
	2. CISO would like answers to the following questions.
		a. How many operational systems does the enterprise have by FIPS 199 level. 
		b. How many assets by Org? How many assets by system? How many assets are not assigned to a system? How many systems have no assets?
		c. How many private ip addresses are in use in the enterprise?
		d. Provide the count of assets by Vendor, by Operating System 
		e. What is quantity of assets defined as GFE? (GFE is defined as any asset with a Windows 10 OS and a private IP address)
  
	3. Requirements
		a. Produce 2 pages in Power BI. 
			i. Page 1: A visualization page answering the questions in section 2.
			ii. Page 2: A definitions page explaining any formulas or acronyms.
		b. The data must be consumable from Power BI into Power Point AND it must be exportable to CSV for end user analysis.
  		c. Users must be able to filter based on Org, system and FISMA Reportable status. 
		d. The report must adhere to the client's style guide included in this repo.
  		e. The developer must demo the resulting report answering any ensuing questions adequetately demonstrating a thorough understanding of Power BI as well as the underlying data.

	4. Tips for Success
  		a. DAX Measures must be incorporated and must be explainable.
   		b. Power Query data transformations must be incorporated and be explainable.
     		c. Report must have a clean asthetically pleasing appearance, telling a concise, consumable story to the end user.
       		d. Data model must adhere to best practices and be explainable.
	 	c. Visualizations must accurately display underlying data with no errors.
   		e. Demo must display a thorough understanding of the underlying data and tell a cohesive data story.

   

