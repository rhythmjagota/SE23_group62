**Reflection on the Process**

Working on the previous project and trying to make it work in 2023 was difficult. Some of the challenges we ran through are listed below:

**Outdated Dependencies:** One major issue was that the project relied on outdated libraries and dependencies no longer supported or compatible with the current environment. This led to compatibility issues and, ultimately, prevented the project from running.

**Lack of Documentation:** Another challenge was the absence of comprehensive documentation. This made it significantly harder to get the project up and running. Few repositories missed critical information about how the setup was supposed to be done. We had to navigate to the previous repository to get basic setup information. Since the most recent update had newer functionalities built on top of the previous projects, the setup of those was an especially difficult task.

**Hardcoded values:** There were many hardcoded values in some projects which proved out to be the major hurdle in understanding the code and the project. It also provided difficulty in testing different scenarios and edge cases. Using hardcoded values for crucial processes might lead to inconsistent results and imprecise errors.

**Inadequate Unit Tests**: Simple unit tests for the project didn't cover all of the functionalities. To make sure the product is accurate and reliable, thorough unit testing is crucial. Many problems were missed because there was insufficient testing before the code was run.

**Assumptions and Implicit Knowledge:** The original developer might have made certain assumptions or relied on implicit knowledge that was not obvious to me. This resulted in confusion and wasted time trying to understand the intricacies of the code.

**Cloud Hosting:** Few services are hosted on the cloud and require us to purchase subscriptions. One project had third-party tools and the GitHub repo asked us to email the contributors to get account details to connect to the database. Even though we emailed them well in advance, we got no response from their end.

**Absence of code formatters:** The code formatters and style checkers were missing in some projects so it became difficult to enforce code formatting as the code did not have the code formatters and we had to manually check and format the code.

**Inadequate Error Handling**: The project required better error handling because it frequently crashed and produced cryptic error messages. For problems to be diagnosed and resolved effectively, error handling must be done effectively.


**Strategies for Improvement in Project 2**

To avoid a similar painful process  in Project 2, we are planning on committing to the following practices:

**Regular Dependency Updates:**

We plan on checking the libraries and dependencies regularly to stay up-to-date on new releases, fix bugs, and implement security patches as they come.

**Thorough Documentation:**

A complete documentation so that it’s easier for us and for future contributors. We plan on including: 

**Setup Instructions:** Installation steps 

**Configuration Options:** Explanations of configurable parameters, options, and settings.

**Troubleshooting Tips:** Fixes to common issues that might come for people who wish to install our project

**Architecture Overview:** Explanation of how all components co-exist

**Version Control and Readme Files:** Usage of version control systems (such as Git) enables change tracking and collaboration. The README.md file is pivotal to the repository as it includes a comprehensive overview of the project description, a list of steps on how to set up the environment and install the application catering to all operating systems, and additionally provides an example showcasing the features and functionalities of the application.

**Modular Code and Comments:** Narrowing down the code to smaller less complex modules helps future developers build on top of the code more efficiently and also helps manage the repository by tracking comments on each update to the code. This will help us revert to previous changes even more quickly.** 

**Testing and Continuous Integration:** We plan on following the CI/CD pipeline to help us catch any regressions or errors as soon as any change is pushed to the repository. We will implement this by creating automated tests and unit tests which will check each component of the code and also verify its expected interactions with other components.

**Backup Plans and Contingencies:** We will identify dependencies which are important to our project and have safety nets or backup options available for those to make sure that the project can always work.

**Regular Knowledge Sharing and Code Reviews:** We shall regularly participate in sessions where we share our new-found knowledge and experiences and how they can be put to use in our project to enhance it. Code reviews will help us improve it, and fix bugs or issues that one person might have missed.

**Stay Informed about Industry Trends:** We plan on staying up-to-date on the latest developments and trends in our industry so that we can keep improving our project. 

By following these practices we believe that we will be able to avoid any issues and troubles in our project.


