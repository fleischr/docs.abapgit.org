---
title: SSL Test
category: setup
order: 20
---

The report [zabapgit_test_ssl](https://raw.githubusercontent.com/abapGit/docs.abapgit.org/main/src/zabapgit_test_ssl.abap) can be used to test the SSL connection to GitHub or any other Git server. Copy and paste the report into your ABAP system (package `$TMP`) and run the report.

### Selection Screen

![ssl_test_selection](img/ssl_test_selection.png)

Note: The default selection will be testing the connection to GitHub. However, you may select a different Git server URL using the value help or enter your own URLs.

### Expected Result

![ssl_test_result](img/ssl_test_result.png)

### Errors and Troubleshooting

If the connection does not work, the output will show an error message. You can click the message to see the detailed response to the HTTP request.

Please see [SSL Setup](guide-ssl-setup.html) for details about the correct setup and troubleshooting tips.
