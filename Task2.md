I. Functional tests:

  1. Upload is successful, but HTML file has incorrect syntax - e.g. HTML     tags are not closed. 
  2. Upload is successful, but HTML file is corrupted - e.g. choose some JPG file and change the extension to HTML.
  3. Upload is successful, but PDF file is empty - e.g. create empty TXT file and change the extension to PDF
  4. Upload is successful, refresh the page and check what will happen
  5. After publishing file refresh the page. Check that file is publish twice or notification will be send twice.
  6. Start the uploading files in two tabs of the browser simultaneously on the same session - see if the file will be uploaded.
  7. If this shared service requires logging in - try to log out during the upload
  8. If this shared service requires logging in - try to log out after upload and check that is it possible to publish a file.
  9. If this shared service requires logging in - try to log out after upload and log In on other account. Check that is this file is visible before publish.
  10. Using several browsers logged in to the same account - check if it is possible to upload a file.
  11. Set function "SEND NOTIFICATION" on do not send - check if notify is send after publish.
  12. Select the file to upload, then select a new file and check which one will be uploaded (whether it is a new file or the original one)
  13. Interrupt the upload and check if the page responds by clicking on any of the components.
  14. Enter a long file name (e.g. over 256 or 512 characters) and try to upload it 
  
  II. Non-functional Tests:
  
    1. Use several workstations (or the e.g. JMeter tool) to check the resistance of the page to load by simulating simultaneous actions.
    2. [UI/UX Tests] - Make sure the buttons are where you expect them. 
    3. [UI/UX Tests] - Make sure are the colours not misleading (e.g. red - UPLOAD, green - CANCEL).
    4. Disconnect the internet while sending a file - check the result.
    5. Try to downsize resolution of your browser and see how the page behaves.
    6. Test the application on unsupported versions of platforms such as Linux or Blackberry
    7. Test applications on unsupported versions of browsers - e.g. older versions of Firefox.
