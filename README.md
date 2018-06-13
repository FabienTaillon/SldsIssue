# Slds App

According to [doc](https://releasenotes.docs.salesforce.com/en-us/winter17/release-notes/rn_lightning_slds.htm), using extends="force:slds" should load slds latest version.
But:

Inspect MyTestApp.app (app.css):

`.slds-page-header {       
  padding:1rem;       
  border-bottom:1px solid rgba(0, 0, 0, 0);  
  border-radius:0;  
  background:rgb(250, 250, 249);  
  background-clip:padding-box;  
  box-shadow:none;  
  border:1px solid rgba(0, 0, 0, 0);  
}`


In [SLDS](http://www.lightningdesignsystem.com/downloads):

`.slds-page-header {  
  padding: 1rem;  
  border-bottom: 1px solid #dddbda;  
  border-radius: 0.25rem;   
  background: #f3f2f2;  
  background-clip: padding-box;  
  -webkit-box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.1);  
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.1);  
  border: 1px solid #dddbda;   
}`

Look at the code in this repo or deploy through sfdx:

[![Deploy](https://deploy-to-sfdx.com/dist/assets/images/DeployToSFDX.svg)](https://deploy-to-sfdx.com)