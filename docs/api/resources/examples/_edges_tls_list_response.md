<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-23T10:07:18Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tRBvdaGClvZ7ezv9Po4fzeDxyV",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tRBvdaGClvZ7ezv9Po4fzeDxyV"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tRBuR0vVAVVwzbLaY0FTAT0IDF",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tRBuR0vVAVVwzbLaY0FTAT0IDF"
				},
				"enabled": true
			},
			"created_at": "2025-02-23T10:07:08Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tRBuUNbM7iX4VvooQFLlO8wjEg",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tRBuUNbM7iX4VvooQFLlO8wjEg"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
