<!-- A brief overview of your proposed changes -->
### Summary & Short description
This pull request was made to add the file upload functionality to Yandex.BinaryUpload, which is an important feature that Yandex.Direct API does not support. The changes were made by using Yandex's own interface API and utilizing cookies.

---


### Related JIRA requests
* ADV-1103
* SCRUM-117

---

### Related PRs
* #32
* #35

---

###  Explanation & Visuals

<!-- use text and graphical explanation -->
This pull request has been made to add the file upload functionality, which is an important feature for publishing Yandex ads from our platform, but not supported by Yandex.Direct API. The changes were implemented using the API that runs Yandex's own interface. The file upload functionality was presented to users by adding a new button on the Adviad APP interface and writing backend services to ensure its operation. Our backend services were used to enable this functionality. The technologies we used include PHP Laravel, Yandex Direct Interface API, MySQL, and Authentication Cookie. The Yandex Direct Interface API is a specially developed programming interface for the Yandex.Direct advertising service. This interface assists advertisers in creating, managing, and optimizing advertising campaigns. Authentication Cookie is a type of cookie that enables users to log in. This cookie allows our users to authenticate their identity when uploading files and ensures that they can only upload files that belong to their own accounts. In addition, our backend services verify and process the properties of the files users want to upload. These processes ensure that the properties of the file being uploaded, such as its size, type, and name, are properly set.

---

### CheckList
- [X] My code matches all coding standards
- [X] I included documentation updates to the coding standards, when needed.
- [ ] I ran CI Tests and Unit Tests locally before submitting.
- [X] My code resolved all of the task's acceptance criteria.

---

#### Changes proposed in this PR:

- <!-- Updated existing component -->
- <!-- Updated places where said component was used -->

#### Acceptance Criteria Scenarios
<!--
List all relevant new/existing Cucumber scenarios from specs folder
Insert your specs folder path here

- [ ] [Show Sprint reconcile header state]
- [ ] [Tap reconcile header's "move back" button]
- [ ] [Tap reconcile header's "merge into sprint" button]
- [ ] [Tap reconcile header's  close button]
-->
