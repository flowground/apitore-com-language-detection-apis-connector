# ![LOGO](logo.png) Language Detection APIs MSP Connector

## Description

A generated MSP connector for the Language Detection APIs API (version 0.0.1).

Generated from: https://api.apis.guru/v2/specs/apitore.com/languageDetectionApis/0.0.1/swagger.json<br/>
Generated at: 2019-05-07T11:17:02+03:00

## API Description

Language detection.<BR />[Endpoint] https://api.apitore.com/api/22

## Authorization

This API does not require authorization.

## Actions

### Language Detection. This supports 53 languages.

> Language Detection.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/langdetect-response">langdetect-response</a><BR />&nbsp; Class: com.apitore.banana.response.org.jsoup.LanguageResponseEntity<BR />

*Tags:* `lang-detect-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `text` - _required_ - Text [10-20 words over is recommended]

### Language Detection for Short Messages. This supports 53 languages.

> Language Detection.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/langdetect-response">langdetect-response</a><BR />&nbsp; Class: com.apitore.banana.response.org.jsoup.LanguageResponseEntity<BR />

*Tags:* `lang-detect-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `text` - _required_ - Text [Short message like tweet is supported]

## License

flowground :- Telekom iPaaS / apitore-com-language-detection-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
