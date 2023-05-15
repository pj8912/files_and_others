# FILEAPI

Some important points on fileapi

- The FileAPI, being a client-side JavaScript API, allows web applications to interact with files on the user's local system through the browser. It provides functionality such as reading file contents, writing to files, and uploading files asynchronously. The FileAPI is primarily used for enhancing user interactions and enabling file-related functionality within web applications.

- With the FileAPI, you can use features like the FileReader object to read the contents of a file, the FileWriter object to write data to a file, and the XMLHttpRequest or Fetch API to upload files to a server.

- The FileAPI is primarily used in web applications to enhance user interactions and enable file-related functionality without requiring traditional file upload forms.

- The FileAPI does not require the use of an enctype attribute.
  - The enctype attribute is typically used in HTML forms to specify how the form data should be encoded and sent to the server when the form is submitted. When handling file uploads, the enctype attribute is set to "multipart/form-data" to indicate that the form data will contain binary file data.

  - However, when using the FileAPI, you are not necessarily working with traditional HTML forms and their associated enctype attribute. The FileAPI allows you to interact with files directly from JavaScript without the need for a form submission.

  - Instead of relying on form submissions, the FileAPI provides methods and events that allow you to access and manipulate files through JavaScript code. You can use features like the FileReader object to read file contents, the FileWriter object to write data to a file, and the XMLHttpRequest or Fetch API to upload files to a server asynchronously.
