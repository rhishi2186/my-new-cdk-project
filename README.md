# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.
The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template

**Prerequisites**: 
AWS CLI installed and configured.
AWS CDK installed.
Node.js 
TypeScript.

****Install following commands**:
#npm install -g aws-cdk

#aws configure (With Access & secrete Code)


#npm install

**Edit the configuration:
**
Update the file paths for static website files in my-new-cdk-project folder.
 configure a custom domain and SSL in the lib/my-new-cdk-project-stack.ts file.

**Deployment**
To deploy the static website infrastructure:

Synthesize the CloudFormation template:
#cdk bootstrap 

**Deploy the stack to AWS** :
#cdk deploy
After the deployment, the output will include the CloudFront distribution URL where your website is hosted. You can visit this URL to access your site.

#npm run test

To destroy the infrastructure using CDK.

#cdk destroy
