<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-12T10:07:03Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2wzVWpsAdmKDm16KAgZgUDGsC7X",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wzVWpsAdmKDm16KAgZgUDGsC7X"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2wzVVcxvKUR6rYpdN3lGjssuA1v",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2wzVVcxvKUR6rYpdN3lGjssuA1v"
        },
        "enabled": true
      },
      "created_at": "2025-05-12T10:06:53Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2wzVVZB9iGxM8uThCgDejcVxYGO",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wzVVZB9iGxM8uThCgDejcVxYGO"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
