# actions-warp

### Usage example:
client warp+doh mode
```
  - name: Set up WARP connection
    uses: sebst/actions-warp@v1
    with:
      tos: YES   # Required. Set to YES to accept the Terms of Service of Cloudflare.
```

### Input Parameters

| Parameter | **Mandatory**/**Optional** | Description |
| --------- | -------- | ----------- |
| tos | **Required** | Accept TOS: Needs to be set to `YES`. Default is `NO`. |
