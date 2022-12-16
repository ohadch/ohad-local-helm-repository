# Local Helm Repository

## Usage

This spins up a local helm repository for testing purposes, and adds it to the helm repos with the name `local`:

```bash
make up
helm repo add local http://localhost:8085
```

After this, you may add the charts to your `local` repository.