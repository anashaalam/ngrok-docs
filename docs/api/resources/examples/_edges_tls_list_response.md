<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-27T10:08:11Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30SB3Ce8VNc3KKShbyZ7M2Sixj6",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30SB3Ce8VNc3KKShbyZ7M2Sixj6"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30SB1sKcwRqDXPl6ncRk3eWb48f",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30SB1sKcwRqDXPl6ncRk3eWb48f"
        },
        "enabled": true
      },
      "created_at": "2025-07-27T10:08:01Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30SB1rKJdsywC0fevEhl0dJ11hE",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30SB1rKJdsywC0fevEhl0dJ11hE"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
