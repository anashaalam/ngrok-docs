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
          "started_at": "2025-07-27T10:07:45Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5549f888vblnederw.local-ngrok-cname.com",
      "created_at": "2025-07-27T10:07:45Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30SAzuRR3oyaL9pwykWu2qXBLXT",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30SAzuRR3oyaL9pwykWu2qXBLXT"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30SAzogdKl4ReBqleN6J42kjj7j",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30SAzogdKl4ReBqleN6J42kjj7j"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5549f888vblnederw.local-ngrok-cname.com",
      "created_at": "2025-07-27T10:07:45Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30SAzpu2hqfGU9vz1uz7xTZTVgc",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30SAzpu2hqfGU9vz1uz7xTZTVgc"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-27T10:07:14Z",
      "description": "Your dev domain",
      "domain": "pleased-famous-ocelot.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30SAw1jNlIbWrEUxxARkP7Fy8jh",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30SAw1jNlIbWrEUxxARkP7Fy8jh"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
