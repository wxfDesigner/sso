# sso
sso you like

Please add mongodb collections and records as below:

User Collection:

{
    "_id" : ObjectId("5c08d6050cac8b9451045715"),
    "guid" : "1",
    "createTime" : ISODate("2018-01-25T06:38:17.000Z"),
    "version" : 0,
    "username" : "bob",
    "password" : "abc123",
    "phone" : "12345678901",
    "email" : "123456@163.com",
    "defaultUser" : false,
    "lastLoginTime" : ISODate("2018-01-25T06:38:17.000Z"),
    "privileges" : [ 
        "USER"
    ],
    "archived" : false
}

OauthClientDetails collection:

{
    "_id" : ObjectId("5c08d89d0cac8b94510457e0"),
    "clientId" : "my-trusted-client",
    "createTime" : ISODate("2018-01-25T06:38:17.000Z"),
    "version" : 0,
    "archived" : false,
    "resourceIds" : null,
    "clientSecret" : "secret",
    "scope" : "read,write,trust",
    "authorizedGrantTypes" : "password,authorization_code,refresh_token,implicit",
    "webServerRedirectUri" : "https://www.baidu.com/",
    "authorities" : "ROLE_CLIENT,ROLE_TRUSTED_CLIENT",
    "accessTokenValidity" : 1800,
    "refreshTokenValidity" : 3000,
    "additionalInformation" : null,
    "trusted" : false
}
