
<!----------------------------------------------------------------------------------------------------------------------
-                                                                                                                      -
-   Created by: MPZinke                                                                                                -
-   on 2022.01.21                                                                                                      -
-                                                                                                                      -
-   DESCRIPTION:                                                                                                       -
-   BUGS:                                                                                                              -
-   FUTURE:                                                                                                            -
-                                                                                                                      -
----------------------------------------------------------------------------------------------------------------------->


# ADO Migration Guide: Work Items

## What Are Work Items?
Use work items to track anything you need to track. Each work item represents an object stored in the work item data store.
Each work item is based on a work item type. And work item types have a unique identifier within an organization or project collection.
The available work item types depend on the process you used when creating your project (Agile, Basic, Scrum, or CMMI).


## BEFORE YOU CONTINUE MAKE SURE YOU UNDERSTAND
<input type="checkbox"/> Work Items can be migrated separately from repos, but they will not be able to link PRs/commits to work items until ADOS repos have been migrated to either GHEC or ADOC.

<input type="checkbox"/> If and when your repos are in GHEC, and after Work Items are migrated, you or your team needs to set up github connection in new ADOC project with their GHEC repo(s).


## How To Migrate
1. Fill out the information below to make sure your information is complete.
2. Make a request by...
3. Await approval


## Needed Information For Migrating
Please fill this out and save it as a PDF with copyable text

1. What do you want migrated?
	<select>
		<option>Team</option>
		<option>Project</option>
		<option>Product</option>
		<option>App</option>
		<option>Other</option>
	</select>

	If other, please specify what
	<input style="width:100%"/>

2. Work Item Scoping

	1. Which do you represent?
		<select>
			<option>Individual Project</option>
			<option>Team</option>
		</select>

		If team, please list the team's name
		<input style="width:100%"/>

	2. Create a work item migration query for what you want to query:

		- "Take only what you need to survive"

		- Your original Work Items will still be available for the foreseeable future if they need to go back and look

		- This query can include test cases if need be

		1. Go to <link\>

		2. <Fill out what you need to\>

		3. Insert the link to your query in ADO below (Please click and drag the textbox to expand it so that the entire URL is visible)

			<textarea style="width:100%"></textarea>

3. Please specify your target project
	<input style="width:100%"/>

4. What are the area and iteration paths (Please click and drag the textbox to expand it so that the entire URL is visible)?

	1. Do you want the entire tree structure migrated?

		- Trees can be migrated and then cleaned-up, restructured, and deleted as needed.

		- If no, you will need to coordinate the migration mapping with the ADO Migration Team.

		<select>
			<option>Yes</option>
			<option>No</option>
		</select>

		<!-- If teams migrating under a product want to share iteration cadence when they weren't in ADOS, recommend to set up new shared iterations at the root level for new iterations moving forward (rather than restructuring old iterations and bulk updating items from those old iterations). -->

5. When are you looking to migrate?

	<input type="date">

	- Does this need to occur after hours?

		<select>
			<option>Yes</option>
			<option>No</option>
		</select>


## What Will Happen


## How To Migrate


---

## Appendix

### Links

