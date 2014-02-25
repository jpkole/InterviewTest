Thank you for your continued interest in Rally's Technical Services Engineer
position.  We’ve been impressed with our conversations so far.  I think you’ll
agree that your description of technical experience isn’t an exact fit, so we
thought we’d try an exercise to help us get a feel for the way you approach
technical problems.  So we’ve created this short data manipulation exercise.
In this exercise, you will prepare a data set for migration.

Please complete the exercise by March 5th.  Submission will be a single zipped
archive containing your documented program and one example datafile and output
set (directory structure up to you).  Entry must include a short README with
instructions.


Exercise:
---------
The City of Baltimore provides open access to city data including citations and
associated fines at:
	https://data.baltimorecity.gov/Financial/Parking-Citations/n4ma-fj3m
	
Our customer wants every citation to be a story in Rally.  Manually obtain a
CSV export containing all citations that occurred on July 4th, 2012.  Write a
program that loads the CSV data, transforms the data, and creates a second
CSV file that is ready for upload into Rally.  The rules for the data going
into Rally are:

   Rally FieldName	Contents of field
   -----------------	--------------------------------------------------------
1. Name			should contain the citation number
2. Description		should contain the Description
3. ViolationDate	should contain the date.  Rally dates are in ISO format
4. PlanEstimate		should contain the amount of the fine (this is an
			integer field)
6. LicenseExpiration	should contain the date of the license plate’s
			expiration.
7. Notes		should contain a bulleted list of:
			- Make of car
			- State the car is from (full text, not abbreviation)
			- License plate number

Keep in mind that we might want to run your script against different extract
date ranges and that we might change our mind about the mappings.  The goal of
this exercise is not to create a perfect solution but to demonstrate how you
approach requests and resolutions.  
