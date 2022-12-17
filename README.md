# Local Helm Repository

## Usage

This spins up the following:
- local helm repository on `http:localhost:8085` adds it to the helm repos with the name `local`
- a local docker registry on `http:localhost:5001`

```bash
make up
helm repo add local http://localhost:8085
```

After this, you may add the charts to your `local` repository.