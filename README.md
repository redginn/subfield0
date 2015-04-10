# subfield0
<p>By inserting |0 URIs into authority 1xx fields, you can leverage your ILS's automatic bibliographic record updating processes (if available) to add |0s into authority controlled fields to prepare your MARC data for linked data.</p>
<p>This is a TaskList for use with Terry Reese's MarcEdit [http://marcedit.reeset.net] on authority records with a Library of Congress control number that takes the control number from the 010 and reformats it into an id.loc.gov URI and inserts the URI into the 1xx|0 of authority records.</p>
<p>Download the TaskList to your computer by clicking on AuthoritySubfield0Task.zip, then clicking View Raw. Extract the file from the zip, then import it into MarcEdit.  (MarcEditor, Tools->Manage Tasks->Import Task->find the file, Open.)
<p>Run the TaskList on authority records before loading them into your system (Open your file in MarcEditor, Tools->Assigned Tasks->Currently Available Tasks->AuthoritySubfield0).  Save the file and translate it back into .mrc before loading the records into your ILS.  This will work whether you are downloading authority records individually or subscribing to an update service.  
If your ILS automatically updates your bibliographic records based on authority updates, your bibs will be updated with |0.</p>
<p>Note: Although the guidelines for |0 [http://www.loc.gov/marc/marbi/2007/2007-06.html#p1] call for a parenthetical organizational designation followed by the ID number, I have chosen to loosely define the ID number as the URI and omit the parenthetical organizational designation since that is implicit within the URI.  If the designation should become necessary at a later date, it would be simple to insert with a global update since the URIs are by nature highly consistent.</p>
