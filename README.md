# Evaluation Data Extraction and Visualization
Group 7 <br/>
Karl Schreiner <br />
Laura Nichols <br />
Yijia  Bai

At the end of each semester, students fill out evaluation forms for all of their professors. The university requires aggregation of this data into a specific spreadsheet form when making personnel decisions. However, the evaluation data can only be exported from the Blue evaluation software as a PDF. Consequently, the data has to be manually extracted and aggregated. This process is time consuming and error prone, so it is only done when required by the university, limiting possible insights into the data in the interim periods.

For our project, we will create a web application for visualizing and analyzing this evaluation data and automating the process of extracting the data into the spreadsheet form required by the university. We will build in the ability to extract data, either through PDF upload or direct integration with Blue, if allowed by the university. Users will then be able to view data according to their permissions (i.e., professors can only view their data, but department chairs can view the data for all of their professors), aggregate the data in various ways (e.g., by professor, section, semester), and export the data into the spreadsheet form required by the university. We will also build in the ability for an administrator to manage user permissions and include Vanderbilt SSO for user login, to ensure the security of the evaluation data.

On the front end, we use Node.js, jQuery, Bootstrap, React, and Redux. This will allow us to create a truly interactive and tailored view. We are not super familiar with back end development, but we plan to pull in a variety of JavaScript libraries in order to keep things running smoothly. We will host this back end using an AWS cloud server. On the database side, we will use Amazon RDS to host several mySQL tables to store login information as well as all of the evaluation data.
