<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-23T10:06:52Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.417iuy7oydrwfbeu3.local-ngrok-cname.com",
			"created_at": "2025-02-23T10:06:52Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tRBsSR7uYKuciygQY8euIx6Zfw",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tRBsSR7uYKuciygQY8euIx6Zfw"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tRBsTXBOqEVCwAej10oq4oeCQN",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tRBsTXBOqEVCwAej10oq4oeCQN"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.417iuy7oydrwfbeu3.local-ngrok-cname.com",
			"created_at": "2025-02-23T10:06:52Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tRBsMaGGAHmKkL7qG0fdh5sh0K",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tRBsMaGGAHmKkL7qG0fdh5sh0K"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
