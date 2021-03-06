## Usage

- Click the `Settings` tab on your own repository, and then click the `Secrets` button to add the following encrypted environment variables:

  | Environment Variables | Description |
  | --------------------- | ----------- |
  | `IBM_CF_USERNAME`       | IBM Cloud user name (email address) |
  | `IBM_CF_PASSWORD` | IBM Cloud password |
  | `IBM_CF_ORG_NAME`(optional) | Organization name, the default is the email address. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_SPACE_NAME`(optional) | Space name, default is `dev`. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_APP_NAME` | App name, fill in according to your preference. |

- Click the `Run workflow` button on the Actions page.
- Wait for the deployment to complete.
- Click the relevant application on the [Cloud Foundry Public](https://cloud.ibm.com/cloudfoundry/public) page to view the access address.

> **TIPS:** You can customize the API address and App memory size through the workflow file.