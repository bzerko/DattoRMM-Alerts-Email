# DattoRMM-Alerts-Email
Takes Datto RMM Alert Webhooks and sends them to an email address

### Webhook
```
{
    "troubleshootingNote": "Please run scandisk and then consult the documentation with the view docs link",
    "docURL": "https://docs.yourdomain.com/alert-specific-kb-article",
    "showDeviceDetails": true,
    "showDeviceStatus": true,
    "showAlertDetails": true,
    "alertUID": "[alert_uid]",
    "alertMessage": "[alert_message]",
	"platform": "[platform]"
}
```
