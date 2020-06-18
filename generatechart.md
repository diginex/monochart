# Generate charts and store in Github page.

```sh
cd incubator
helm package monochart
helm repo index --url https://diginex.github.io/monochart/ .
mv index.yaml ../docs
```