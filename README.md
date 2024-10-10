<h1>Help Desk Ticket: Drive Access Troubleshooting</h1>

<h2>Description</h2>
A user had the following issue:<br>
I can’t access drive F on my computer. I need to save some files on this drive. Please advise.

<h2>Troubleshooting Process</h2>

- <b>Theory 1: Drive F is not available on this computer: Went into File Explorer > This PC and the F Drive does appear there; when I click on the drive I get the error message “F:\ is not accessible” and “Access denied”.</b>

- <b>Theory 2: There is an issue with permissions: Right clicked on the F Drive, Selected “Properties”, went to Security Tab and clicked “Advanced”, for Owner it says “Unable to display current owner”. I clicked on the link to “Change Owner” and entered the admin password. From there, I entered “L” in the space for the name, and added the local account to the list and gave them “Full Control” under permissions. I was then able to access the F Drive. I then saved a file to the F Drive to test functionality and it worked.</b>

<h2>Resolution</h2>

- <b> Resolution (Internal): The user did not have permission to access the F Drive. I went into the F Drive Properties > Security > Advanced and added the local account to the list with full control.
- <b> Resolution (Client-Facing): It looks like the permissions that had been set did not allow you to access Drive F. I went in and changed the permissions so that you can now save to the F Drive.

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
