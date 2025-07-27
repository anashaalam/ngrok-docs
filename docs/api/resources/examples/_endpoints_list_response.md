<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-27T10:08:06Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30SB1vU7rePvskY0BBCIwpN02Be",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30SB1vU7rePvskY0BBCIwpN02Be"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30SB2SIGYNpm8HXEvLms9ggZb1g",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-27T10:08:06Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30SB2SIGYNpm8HXEvLms9ggZb1g",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-27T10:08:04Z",
      "hostport": "c765981b87f3.ngrok.paid:443",
      "id": "ep_30SB2ExHxiqBkQQQl7122FvdHkj",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30SAvgKcBMejOeipDQZjJp3ZefP",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://c765981b87f3.ngrok.paid",
      "tunnel": {
        "id": "tn_30SB2ExHxiqBkQQQl7122FvdHkj",
        "uri": "https://api.ngrok.com/tunnels/tn_30SB2ExHxiqBkQQQl7122FvdHkj"
      },
      "tunnel_session": {
        "id": "ts_30SB2HSzNHfBSZLLyPvlY8s7IsY",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30SB2HSzNHfBSZLLyPvlY8s7IsY"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-27T10:08:04Z",
      "upstream_url": "http://localhost:80",
      "url": "https://c765981b87f3.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-27T10:08:01Z",
      "domain": {
        "id": "rd_30SB1vU7rePvskY0BBCIwpN02Be",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30SB1vU7rePvskY0BBCIwpN02Be"
      },
      "edge": {
        "id": "edgtls_30SB1rKJdsywC0fevEhl0dJ11hE",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30SB1rKJdsywC0fevEhl0dJ11hE"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30SB1qsPfS1WiPyapOGPghdoJV5",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-27T10:08:01Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
