# Testing

## Test Plan

Test Case 1 should test all of the following: <br>
- makes sure the map page loads from the splash page. <br>
- makes sure the map itself loads. <br>
- makes sure the "Allow your location" button works. <br>
- makes sure all markers are present and show the accurate locations of all toilets on the map. <br>

Test Case 2 should test all of the following: <br>
- makes sure the type page loads from the splash page. <br>
- makes sure the table itself loads. <br>
- makes sure the table can be filtered by search. <br>
- makes sure the table can be filtered by distance. <br>

Test Runs \

| Use-Case ID | Requirement ID | Test Case | Status | <br>
| UC1 ------- | FR1.1 -------- | TC1 ----- | PASS   | <br>
| UC1 ------- | FR1.2 -------- | TC1 ----- | PASS   | <br>
| UC1 ------- | FR1.3 -------- | TC1 ----- | PASS   | <br>
| UC1 ------- | FR1.4 -------- | TC1 ----- | PASS   | (it only centres on the user's location, however, it doesn't put a marker where the user is)<br>
| UC1 ------- | FR1.5 -------- | TC1 ----- | PASS   | <br>
| UC2 ------- | FR2.1 -------- | TC2 ----- | PASS   | (but only displays the locations, not the names) <br>
| UC2 ------- | FR2.2 -------- | TC2 ----- | PASS   | <br>
| UC2 ------- | FR2.3 -------- | TC2 ----- | FAIL    | <br>
| UC2 ------- | FR2.4 -------- | TC2 ----- | FAIL    | <br>
<br>
FR2.3 and FR2.4 are both a fail as I was unable to get the system to correctly find and display the distance from user to the toilets.<br>

![](images/testing1.1.png) <br>
The above is a photo of the map page before permissions are allowed.<br>
<br>
![](images/testing1.2.png) <br>
The above is a photo of the page asking for permission to use the user's location.<br>
<br>
![](images/testing1.3.png) <br>
The above is a photo of the map after permissions have been granted.
<br>
--------------------------------------
![](images/testing2.png) <br>
The above is a photo of the "type" page.
