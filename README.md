# owncloud-test-report
This is a repository for store test reports.

## Rules
### Main Folder naming
Foramt: V.V.V - YYYYMMDD - Reporter

For example: 8.2.1 - 20150101 - Chris

### Test Case Folder naming
A main foler may contains few or many Test Case folders.
Each folder should map to one Test Case name.

For example: [FM.0-FI.0-00]

### Action Folder
Tester should create Action folders under a Test case folder for test that failed.

For example: [FM.0-FS.0-22] Create File (Pre Action)

### Data Files
Each Action folder should contains 4 text files as below:
* Sampler result
* Request
* Response data
* Response Assertion

### Sample
* 8.2.1 - 20150101 - Chris
    * [FM.0-FI.0-00]
        * [FM.0-FS.0-22] Create File (Pre Action)
            * Sampler result
            * Request
            * Response data
            * Response Assertion
