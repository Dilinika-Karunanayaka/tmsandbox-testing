# TrdeMe Sandbox Home Page Test Cases

List the test cases for the home page (https://www.tmsandbox.co.nz/).

The home page of a website serves as the gateway for users, offering their first impression and navigation point. 
This document outlines a comprehensive set of test cases tailored for the home page of https://www.tmsandbox.co.nz/. 
These test cases aim to ensure the functionality, usability, performance, security, accessibility and compatiability of the home page.

## Functional Test Cases

1. Verify the home page loads successfully and all essential elements are dispalyed correctly.
> - **Suits:** Smoke, Sanity, Regression 
> - **Automation:** Yes
> - **Reason:** Critial for the initial access fo the site, ensure page is accessible.
	
2. Ensure that every hyperlink on the home page of Trade Me sandbox is working as expected and redirectiong to the correct destination without any error.
> - **Suits:** Smoke, Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Emsure navigation accross the site is not broken

3. Verify the login/Registration links redirects to the correct page and work as expectd.
> - **Suits:** Smoke, Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Requir for user registration and authentication process.

4. Verify the navigation menu is displayed and each item navigates correctly.
> - **Suits:**  Smoke,Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures proper navigation and content discovery.

5. Verify the search bar is visible and functional. Allowing users to perform seraches and receive relevent results. 
	- verify search bar display correct place holder text
	- Vefiry Search suggestions appear in drop down list are relevent to the entered search.
	- Verify the search results are relevent to the query.
> - **Suits:** Smoke, Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Primary functionality for user interaction

6. Verify footer global links works as expected
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures proper navigation and content discovery.

7. Verify Home page member option items (Marketplace/Jobs/Motors/Property/services) are redirect to the expected page and retrive releven information for logged in user.
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:**  Ensures proper navigation and content discovery.
	
8. Verify all Tranding category links are fucntion peopperly and lead to the correct item detail page.
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures proper navigation and content discovery.

## Usability Testing
1. Verify the home page is responsive on various devices.
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures usability across different devices.

2. Verify the layout and elements adjust correctly on different screen sizes. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes (Visual regression using precy or Applitools or image comparison)
> - **Reason:** Ensure the better validation of readability

3. Verify the UI design is consistent. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes (Visual regression using precy or Applitools or image comparison)
> - **Reason:** Ensure the consistency of the web page

4. Verify error messages are displayed properly.
> - **Suits:**  Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures proper feedback to users.

5. Verify buttons change appearance on hover and click. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes  (Visual Regression)	
> - **Reason:** Visual inspection ensures accurate UI behavior.

## Performance testing
1. Verify the home page loads within an acceptable time frame.
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures optimal performance.

2. Verify the search reaults loads within an accepatable time frame. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes		
> - **Reason:** Ensures optimal performance of search function.

3. Verify the home page remains functional under high traffic. 
> - **Suits:** Full Regression
> - **Automation:** Yes	
> - **Reason:** Ensures stability under load conditions.

## Security Testing
1. Verify password fields are masked. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes		
> - **Reason:** Ensures user privacy

2. Session Management - verify sessions expire after a period of inactivity and Verify users are logged out securely.
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures proper session handling.

## Accessibility Testing 
> - **Automation:** No
> - **Reason:** Check below are accroding to the WCAG 2.1 standards
1. Verify all interactive elements are keyboard accessible.
> - **Suits:** Sanity, Regression
2. Verify the home page is compatible with screen readers. 
> - **Suits:** Sanity, Regression
3. Verify text and elements have sufficient color contrast.
> - **Suits:** Sanity, Regression
4. Verify all images have descriptive alt text.
> - **Suits:** Sanity, Regression

## Compatibility Test Cases
1. Verify the home page functions correctly on different browsers (cross browser testing). 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures cross-browser compatibility.

2. Verify the home page functions correctly on different OS. 
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:** Ensures compatibility across operating systems.

3. Verify the home page displays and function correctly in different device orientations (Cross device comaptibility). (Sanity, Regression)
> - **Suits:** Sanity, Regression
> - **Automation:** Yes
> - **Reason:**	Ensures proper display on mobile devices.

4. Verify text and layout scale properly on zooming. 
> - **Suits:** Sanity, Regression
> - **Automation:** No
> - **Reason:** Ensures proper display on mobile devices.

