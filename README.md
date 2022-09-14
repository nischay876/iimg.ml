## [Docs](https://docs.iimg.ml)
## [Customizations](https://docs.iimg.ml/customizations)
## [Custom Domain](https://docs.iimg.ml/custom-domain)
## [Features & Limits](https://docs.iimg.ml/features-and-limits)
## [About](https://docs.iimg.ml/about)
### [ShareX Config](https://iimg.ml/dl)
```json
{
  "Version": "14.0.1",
  "DestinationType": "ImageUploader, TextUploader, FileUploader",
  "RequestMethod": "POST",
  "RequestURL": "https://iimg.ml",
  "Headers": {
    "Authorization": "anonymous",
    "X-OG-Title": null,
    "X-OG-Description": null,
    "X-Webhook-Url": null,
    "X-OG-Author": null,
    "X-OG-Author-Url": null,
    "X-OG-Provider": null,
    "X-OG-Provider-Url": null,
    "X-OG-Color": "#2f3136",
    "X-Domain": "iimg.ml"
  },
  "Body": "MultipartFormData",
  "FileFormName": "file",
  "URL": "{json:.resource}",
  "ThumbnailURL": "{json:.thumbnail}",
  "DeletionURL": "{json:.delete}",
  "ErrorMessage": "{response}"
}
