[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
# Salt Edge Authenticator SCA Service SDK Changelog

## 1.4.0 (2021-04-12)
### Add
* Support of Geolocation info  
* Support of User Authorization Type info  
**Note: Should be added migration for `Transaction_Authorization`. Add `confirmLocation` and `confirmAuthorizationType` fields.**  

## 1.3.0 (2020-06-30)
### Add 
* ServiceProvider.getProviderConfiguration()

### Change
* change Configuration model: add 
* change Consent model

### Remove
* ServiceProvider.getProviderCode()
* ServiceProvider.getProviderSupportEmail()
* ServiceProvider.getProviderLogoUrl()

## 1.2.1 (2020-06-16)
### Change
* change ServiceProvider.onAuthenticateAction() result type to AuthorizationContent

## 1.2.0 (2020-04-14)
### Add
* Consent management feature

## 1.1.0 (2020-03-19)
### Add
* Instant Action feature
* UserIdentity(userId, accessToken, accessTokenExpiresAt) to ServiceProvider.getUserIdByAuthenticationSessionSecret() and to ScaSdkService.onUserAuthenticationSuccess() 

## 1.0.1 (2020-03-18)
### Change
* Small bug fixes

## 1.0.0
### Initial features
- Enrollment
- Instant Enrollment
- Pending Authorizations
  
----
Copyright © 2019 Salt Edge. https://www.saltedge.com  
