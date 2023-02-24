# egeria-connector

egeria connector currently only supports getAssetInfo requests.

## Quick Start

Build the server:

```bash
make build
```

Run the server:

```bash
make run
```

Send request to the server:

```bash
curl -X POST localhost:8080/getAssetInfo -d '{"assetID": "AssetID", "operationType": "read"}' -H "Content-type: application/json"   -H "X-Request-Datacatalog-Cred: QQQ"
```

Stop the server:
```bash
make terminate
```
