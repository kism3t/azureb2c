# azureb2c
Sample Service secured with Azure B2C

## Set  Up
- crate a azure portal account
- execute steps in Create Azure B2C Tenant https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-tenant#create-an-azure-ad-b2c-tenant
- create an app registration with this tutorial https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications?tabs=app-reg-ga
- AND an application Secret with https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications?tabs=app-reg-ga
  - Client Secret Name: `clientsecret`
  - Value: `RZe8Q~ntAp3DKsEWvMkNpcJgj3TujYNazXb8Hbus`
  - SecretId: `b0bea25a-4e23-47c4-a00b-36bfc4902858`
- Create a Sign Up and Sign In User Flow https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-user-flow#create-a-sign-up-and-sign-in-user-flow
  - Optional Continue to Password forgot Flow and User Profile Edit flow
- Go to to create an angular app https://learn.microsoft.com/en-us/azure/active-directory-b2c/configure-authentication-sample-angular-spa-app