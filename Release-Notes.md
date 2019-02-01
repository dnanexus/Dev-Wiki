### Release for 28-Jan-2019
- Refactor internal account for cluster jobs
- Refactor the file status caching logic for Apollo

### Release for 21-Jan-2019
- Refactor internal authentication server
- Refactoring Azufre-specific code for the Platform to make more efficient.

### Release for 15-Jan-2019
- Refactoring the filecloser functionality to address bugs.
- Additional monitoring code with Prometheus added to file uploader.
- Continued migration  of existing SSO users  to  Okta SSO

### Release for 08-Jan-2019
- Concurrent Org Worker Limits:All  orgs that do not have  custom concurent worker limits will default to a maximum of 500 concurrent workers.
- Refactoring of API servers for Okta tokens (impacts only customers moving to Okta SSO)
- Refactoring of Nucleus for compatibility with MongoDB 3.4
- Refactoring to fix bugs in dx_download

### No Release for 01-Jan-2019

### No Release for 25-Dec-2018

### Release for 18-Dec-2018
- Updates to the SCIM server for specific customers to integrate with the DNAnexus Platform Okta authentication server (no impact for all other customers)

### Release for 11-Dec-2018
- Deprecated command line interface (CLI) commands "dx sh" and "dx exit"
- Internal refactoring of code, including adding internal monitoring and alerting functionality

### Release for 04-Dec-2018
- Added i18n/I10n support to allow the user interface to recognize the user's language selection

### Release for 27-Nov-2018
- Refactoring external API servers to support Ubuntu 16.04 and configure for autoscaling
- Ability of the user to archive without requiring support intervention (AWS-East only)
- Augmentation of the MongoDB server with AWS Aurora server (AWS only) for select customers
- Support for HTTPS access for JupyterLab

### No Release for 20-Nov-2018

### Release for 13-Nov-2018
- Updated the download proxy service to handle large volume of big files
- Movement of SSO functionality from the internal Auth Server to Okta for an existing customer

### Release for 06-Nov-2018
- Custom expiration dates on tokens
- User's profile now allows email preferences
- Turned on the load balancer on the internal API server.

### Release for 30-Oct-2018
- Upgraded the nginx webserver to V15
- Refactoring of the job manager to a high availability status
- Allowing users to see the public symlink URL
- Upgrade to REACT to V16 of the Javascript library

### Release for 23-Oct-2018
- Removed the social media links on the landing page of the Platform
- Alerts to org admins when the audit trail is turned off (a configuration setting)

### No Release for 16-Oct-2018

### Release for 9-Oct-2018
- Deployment of the Apollo functionality of the Translational Informatics Suite to appropriately licensed users
- Refactoring code for data egress

### No Release for 1-Oct-2018


### Release for 25-Sep-2018
- Refactoring of the beta-Apollo code (Translational Informatics Suite)
- Refactoring of data egress functionality
