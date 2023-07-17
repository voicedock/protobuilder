# protobuilder
Proto builder (based on bufbuild/buf)

## Generate
```bash
docker run --rm -w "/work" -v "$(pwd):/work" ghcr.io/voicedock/protobuilder generate ./proto --template ./proto/buf.gen.yaml
```

## Manual build protobuilder image
```bash
docker build -t ghcr.io/voicedock/protobuilder .
```
