# LTFS Build docker action for Fedora28

This action builds the LTFS package on Fedora28

## Inputs

### `destination`

**Required** Destination of install。 Default is `/tmp/ltfs`。

## Outputs

None

## Usage

```
uses: LinearTapeFileSystem/Fedora28-Build@v1.0
with:
  destination: '/tmp/ltfs'
```
