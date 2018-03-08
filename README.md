# mypatashala

Login API:

http://149.129.130.116:64352/school/app/securityrsrc/login

Header: Base64(username:password)

Example user id’s:
Teacher
Username: Sam.Khumanthem
Password:123456

Response:

{
  "data": {
    "user": {
      "lastName": "Khumanthem",
      "lastUpdated_dttm": 0,
      "resourceId": "Res1519826000361",
      "addresses": [
        {
          "country": "India",
          "resource": null,
          "city": "Hyderabad",
          "postalCode": 500080,
          "addressLatitude": "17.4555006",
          "effectiveStatus": false,
          "addressLongitude": "78.4901437",
          "district": "Hyderabad",
          "addressLine1": "Kharkana",
          "addressLine2": "Secunderabad",
          "addressLine3": null,
          "state": "Telangana",
          "addressLine4": null
        }
      ],
      "ssnID": "142325869654",
      "schoolbranch": {
        "country": {
          "stateEnabled": true,
          "countryCode": "IND",
          "address3Enabled": true,
          "districts": null,
          "address2Enabled": true,
          "address4Enabled": true,
          "countryName": "INDIA",
          "address1Enabled": true,
          "postalCodeEnabled": true,
          "cityEnabled": true,
          "states": null
        },
        "lastUpdated_dttm": 1519825636000,
        "city": "Hyderabad",
        "coEd": false,
        "postalCode": 500026,
        "classes": null,
        "branchLongitude": "78.506033",
        "branchEnabled": true,
        "schoolCalendars": null,
        "school": null,
        "teachers": null,
        "addressLine1": "8-43-17/25, Wellington Rd",
        "addressLine2": "Krishnapuri, West Marredpally",
        "addressLine3": "Secunderabad",
        "state": {
          "dateTime": 1515330815000,
          "country": null,
          "stateEnabled": true,
          "stateName": "TELANGANA",
          "effectiveDateTime": 1515330815000,
          "districts": [],
          "stateCode": "IND-TS"
        },
        "branchType": null,
        "addressLine4": null,
        "created_dttm": 1519825636000,
        "branchLatitude": "17.4559811",
        "branchId": "BRANCH1519825636044",
        "lastUpdatedBy": "Abraham",
        "classSubjects": null,
        "branchName": "Hyderabad",
        "sections": null,
        "categoryType": null,
        "effectiveDateTime": 1515332915000,
        "createdBy": "Abraham",
        "district": {
          "dateTime": 1515331715000,
          "country": null,
          "districtCode": "IND-TS-RR",
          "districtName": "Rangareddy",
          "effectiveDateTime": 1515331715000,
          "districtEnabled": true,
          "state": null
        }
      },
      "resourceAttributes": [
        {
          "resource": null,
          "effectiveDate": 0,
          "parentId": null,
          "effectiveStatus": true,
          "resourceType": "TEACHER"
        }
      ],
      "deviceStatus": false,
      "firstName": "Sam",
      "phone_primary": "9999999999",
      "school": {
        "lastUpdatedBy": null,
        "lastUpdated_dttm": null,
        "schoolFullName": "Olive Learning center",
        "schoolBranches": null,
        "schoolEnabled": true,
        "effectiveDateTime": 1515332915000,
        "createdBy": null,
        "schoolNameShort": "OLC",
        "teachers": null,
        "schoolId": "SCHOOL1519783769673",
        "schoolMotto": "Building lives for future",
        "currencyCode": null,
        "created_dttm": null,
        "schoolEstablishedDate": null
      },
      "personalEmailId": "sam@olive.com",
      "resourceEnabled": true,
      "effectiveDate": 0,
      "created_dttm": 0
    }
  },
  "result": true
}

2.  Parent
Username: teacher
Password:123456



