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

##### Activating Yandex on Adviad Platform

![ScreenshotAdviadAPP-Inventory-Page--Select-Yandex](https://user-images.githubusercontent.com/7951872/229355836-204e79f7-fe11-4a72-ae50-1f51d97c026c.png)

##### Yandex Creative uploading via Adviad Platform

![ScreenshotAdviadAPP-Programatic-creative-Page--Upload-html-creative-Yandex](https://user-images.githubusercontent.com/7951872/229355838-d5b66dcf-7dd9-4353-b3c7-1fbe87d2c0ac.png)

##### Creative upload in Yandex Direct interface

![Screenshot-Yandex-APP--Upload-Banner](https://user-images.githubusercontent.com/7951872/229355841-ecdbe740-41d1-4e39-9ecb-29d5f5917ec2.png)

---

### CheckList

- [X] My code matches all coding standards
- [X] I included documentation updates to the coding standards, when needed.
- [ ] I ran CI Tests and Unit Tests locally before submitting.
- [X] My code resolved all of the task's acceptance criteria.

---

### Acceptance Criteria Scenarios

- [X] The uploaded files must be within the specified size limits.
- [X] Supported file types should be uploaded.
- [X] If an error occurs during the file upload process, an appropriate error message should be displayed to the user.
- [X] Files should be transferred correctly to Yandex.Direct API.
- [X] During file uploading, the system's performance should not be reduced.

---

### Required Reviewers
1. @alihuseynIi
2. @sonaazizova
