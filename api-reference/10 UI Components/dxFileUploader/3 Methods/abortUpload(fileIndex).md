---
id: dxFileUploader.abortUpload(fileIndex)
---
---
##### shortDescription
Cancels the file upload.

##### param(fileIndex): Number
The index of the file for which the upload is cancelled.

---

    <!-- tab: JavaScript -->
    var uploadControl = $("#uploaderContainer").dxFileUploader("instance");
    uploadControl.abortUpload(1)

[note]

The **abortUpload** method works differently in the following [upload modes](/api-reference/10%20UI%20Components/dxFileUploader/1%20Configuration/uploadMode.md '/Documentation/ApiReference/UI_Components/dxFileUploader/Configuration/#uploadMode'):

- **useForm**: The method is not supported in this mode.

- **useButtons**: Cancels the file upload and makes the file available for upload.  

- **instantly**: Cancels the file upload.

[/note]
