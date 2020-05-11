## Prerequisites

OCaml and `opam` are needed. Install them via your preferred package manager.
Solo5 with the `hvt` backend are installed automatically when executing the steps
below.

## Run

Hit:

```
mirage configure -t hvt
make depend
make
solo5-hvt console.hvt
```

