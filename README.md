### NGINX Configuration tree structure

```
etc/
└── nginx/
├── api_conf.d/ ………………………………… Subdirectory for per-API configuration
│   └── ..._api.conf …… Definition and policy of your services API
├── api_backends.conf ………………… The backend services (upstreams)
├── api_gateway.conf …………………… Top-level configuration for the API gateway server
├── api_json_errors.conf ………… HTTP error responses in JSON format
├── conf.d/
│   ├── ...
│   └── existing_apps.conf
└── nginx.conf
```