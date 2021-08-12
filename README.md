# Hello world docker action

This action allow you to restart your k8s deployment, now for testing purposes, 2 main feature
- omit the `image-name` and it will do the restart for your deployment
- or set the `image-name` for it to run set the image to you deployment

## Inputs

## `server-url` 
## `token`
## `deployment`
## `image-name`
## `namespace`

## Outputs

no for now

## Example usage

```yaml
      - name: Deploy new version
        uses: Foxhound401/k8s-rollout-action@v1
        with:
          server-url: $SERVER_URL
          token: $TOKEN
          deployment: $DEPLOYMENT
          namespace: "staging"
```
