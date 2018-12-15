# docker-pigz

Pigz running in an alpine linux [github](https://github.com/alpinelinux)|[https://www.alpinelinux.org](https://www.alpinelinux.org) container.

## Usage

```
# just an example.  use whichever options you prefer
docker run --rm -d -v /path/to/file:/opt/share/pigz/file quay.io/genevera/docker-pigz -q -Nm -9 /opt/share/pigz/file
```
