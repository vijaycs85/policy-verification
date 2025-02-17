# Changelog: Policy Verification

## Releases

### 1.1.0, 2022-03-29
- Upgraded Symfony packages to 4.x.

### 1.0.1, 2020-06-30
- Allow passing policies to provide actions. (#9)

### 1.0.0, 2020-02-28
- First stable release.
- Improved performance by not scanning vendor folder recursively search for policy check classes. (#8)

### 1.0.0-beta1, 2019-10-23
- Provide the method `skipCheck()` to be able to skip the policy check to be verified.

### 1.0.0-alpha5, 2019-03-07
- Make the policy check to fail by default if there are no result returned from the check() method.

### 1.0.0-alpha4, 2019-03-01
- Added two new methods to check interface: setResultPassMessage() and setResultFailMessage(). 

### 1.0.0-alpha3, 2019-03-01
- Added new command option data-exclude-output.

### 1.0.0-alpha2, 2019-02-28
- Imeplemented methods for checks requirements verification.

### 1.0.0-alpha1, 2019-02-21
- Initial release.
