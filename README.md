# Adding a custom domain to Azure:

  - Note: This step assumes that a Wordpress Virtual Machine has been already deployed on Azure.

##  Link your IP address to your domain name.
  - An IP address has been created and pointing to your website during the deployment process.

  - The deployed IP address will need to be pointing at the custom domain purchased from 3rd party using this steps:
      -  Go to azure portal.
      -  In the left panel click on + sign to add a custom domain.
      -  Enter the custom domain name and click on validate.

## Record Validation
  - In the record validation section do the following:
      -  Type your host name.
      -  for instance: example.com
    
      - Verified your domain ownership by creating A name record domain service provider.
- This will verify you and your domain name should resolve to your IP address.
