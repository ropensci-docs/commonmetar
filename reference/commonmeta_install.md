# Install latest version of commonmeta

Downloads binary from
[commonmeta](https://github.com/front-matter/commonmeta) releases, and
installs in system wide cache.

## Usage

``` r
commonmeta_install(os = NULL, arch = "x86_64", force = FALSE)
```

## Arguments

- os:

  Operating system, one of "Linux", "Windows", "Darwin". Defaults to
  current operating system. Will be guessed automatically.

- arch:

  Architecture

- force:

  Whether to force a re-install/trigger an update.

## Examples

``` r
if (FALSE) { # \dontrun{
commonmeta_install()
} # }
```
