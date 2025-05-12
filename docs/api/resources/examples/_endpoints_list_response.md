<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-12T10:06:58Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2wzVVb4EpZjHVKGw3ejMzJdpEYk",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wzVVb4EpZjHVKGw3ejMzJdpEYk"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wzVWGL4OwIqrtb5qD3Oa0lsUZT",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-12T10:06:58Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2wzVWGL4OwIqrtb5qD3Oa0lsUZT",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-12T10:06:55Z",
      "hostport": "5229ae24a213.ngrok.paid:443",
      "id": "ep_2wzVVshNfOaKIBtOJsjQjRaDVlx",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2wzVTVePGlfZDyOEaGxuaQJ2bK0",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://5229ae24a213.ngrok.paid",
      "tunnel": {
        "id": "tn_2wzVVshNfOaKIBtOJsjQjRaDVlx",
        "uri": "https://api.ngrok.com/tunnels/tn_2wzVVshNfOaKIBtOJsjQjRaDVlx"
      },
      "tunnel_session": {
        "id": "ts_2wzVVq4LVtZtlxDgSfXiVQUce4Q",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2wzVVq4LVtZtlxDgSfXiVQUce4Q"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-12T10:06:55Z",
      "upstream_url": "http://localhost:80",
      "url": "https://5229ae24a213.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-12T10:06:53Z",
      "domain": {
        "id": "rd_2wzVVb4EpZjHVKGw3ejMzJdpEYk",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wzVVb4EpZjHVKGw3ejMzJdpEYk"
      },
      "edge": {
        "id": "edgtls_2wzVVZB9iGxM8uThCgDejcVxYGO",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2wzVVZB9iGxM8uThCgDejcVxYGO"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wzVVYRIYd5nG524sJWoYIUjzPC",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-12T10:06:53Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
