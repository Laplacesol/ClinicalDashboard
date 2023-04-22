 _______ _                 _______             _______ _________ _______ _________ _______ _________ _______ 
(  ____ ( \      |\     /|(  ____ )           (  ____ \\__   __/(  ____ \\__   __/(  ____ \\__   __/(  ____ \
| (    \/ (      | )   ( || (    )|           | (    \/   ) (   | (    \/   ) (   | (    \/   ) (   | (    \/
| (__   | |      | |   | || (____)|           | (_____    | |   | |         | |   | (__       | |   | (_____ 
|  __)  | |      | |   | ||     __)           (_____  )   | |   | |         | |   |  __)      | |   (_____  )
| (     | |      | |   | || (\ (                  ) |    | |   | |         | |   | (         | |         ) |
| )     | (____/\| (___) || ) \ \__          /\____) | ___) (___| (____/\___) (___| (____/\___) (___/\____) |
|/      (_______/(_______)|/   \__/          \_______)/_______/(_______/\_______/(_______/\_______/\_______)

## Hospital Resource Management Shiny App

This is a Shiny app designed to help hospital staff manage hospital resources. The app has three tabs: "Admissions," "Bed Availability," and "Staff Workload."

### Features

- The "Admissions" tab displays a table of patient admissions data, including patient ID, age, gender, department, admission date, length of stay, doctor, and bed type.
- The "Bed Availability" tab displays a bar chart of bed availability by bed type.
- The "Staff Workload" tab displays a bar chart of the number of patients assigned to each doctor.

### Installation and Usage

To use this app, you will need to have R and the following packages installed: `shiny`, `shinydashboard`, `DT`, `dplyr`, and `ggplot2`.

Once you have the necessary packages installed, you can run the app by opening the `app.R` file in RStudio and clicking the "Run App" button.

### Data Input

The app uses sample data to demonstrate its functionality. You can replace this data with your own data by modifying the `sample_data` data frame in the `app.R` file. 

### Acknowledgements

This app was created by ChatGPT, a large language model trained by OpenAI, based on the GPT-3.5 architecture.

### License

This app is licensed under the MIT License. See the LICENSE file for more information.
