---
id: agile-web-story-templ
title:  Agile Web Story Template
sidebar_label: Agile Web Story Template
---


## Templates for common Web UI story

---

#### User Story 1: List and table 
##### Description
As a user I want to see a list things


#### Acceptance Criteria

- list of columns to be displayed
- Sorting by each columns
- Pagination
- wildcard search field
- If data takes long show loader
- When the list is empty show empty state
- the table be responsive
- pagination must be configurable by the user
- the table must be styled according to the UI/UI standards
- API errors must handled according to API standard


### User Story 2: Create Details page 

##### Description

As a suer I want to add new items to the list 

##### Acceptance Criteria

- Clicking on the list item must open a details page
- All the fields must be empty
- Add fields (List of all the fields)
- Validate fields (list of fields)
- Validate special format fields (date and email)
- Unique fields (fields that should not allow duplication e.g name of an item )
- labels and error messages according to forms standards
- Save button and Back button according to UI forms standard
- Prompt user if information will be lost when leaving the    create page UI/IX standard
- Save button must be disabled until the form is valid
- API errors must handled according to API standard
