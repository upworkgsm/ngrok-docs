<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-23T10:07:13Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tRBuONwRaduT9iXlMk9ALkbKMK",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tRBuONwRaduT9iXlMk9ALkbKMK"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tRBv33On3yVB1iIsP2OA9aqh4f",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-23T10:07:13Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tRBv33On3yVB1iIsP2OA9aqh4f",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-23T10:07:11Z",
			"hostport": "a7d2a96143e6.ngrok.paid:443",
			"id": "ep_2tRBurzwremL4GmbxqorNqjE2TK",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tRBsGTh3IEOemBZyig3XDMDZzu",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://a7d2a96143e6.ngrok.paid",
			"tunnel": {
				"id": "tn_2tRBurzwremL4GmbxqorNqjE2TK",
				"uri": "https://api.ngrok.com/tunnels/tn_2tRBurzwremL4GmbxqorNqjE2TK"
			},
			"tunnel_session": {
				"id": "ts_2tRBureFDQahU2alYGXxxSlww68",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tRBureFDQahU2alYGXxxSlww68"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-23T10:07:11Z",
			"upstream_url": "http://localhost:80",
			"url": "https://a7d2a96143e6.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-23T10:07:09Z",
			"domain": {
				"id": "rd_2tRBuONwRaduT9iXlMk9ALkbKMK",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tRBuONwRaduT9iXlMk9ALkbKMK"
			},
			"edge": {
				"id": "edgtls_2tRBuUNbM7iX4VvooQFLlO8wjEg",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tRBuUNbM7iX4VvooQFLlO8wjEg"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tRBuSjJ8VBRdfr0Z1zF5JWdqMz",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-23T10:07:09Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
