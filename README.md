# repo-info

**Show Tarball URL and SHA-256 checksum for a GithUb repo, copying checksum to clipboard.**

Requirements:

- [Homebrew](https://brew.sh/) Package manager for OS X
- [tomkyle/homebrew-daily](https://github.com/tomkyle/homebrew-daily) My Homebrew tap for daily work.

## Homebrew Installation (OS X)


The *linear-tiff* bash script can be installed by a Homebrew formula, which itself is part of the [tomkyle/homebrew-negatives](https://github.com/tomkyle/homebrew-negatives) tap. 

```bash
# Install tap, opt
$ brew tap tomkyle/daily

# Install formula
$ brew install repo-info
```

As “tapping” first is not neccessarily needed, you can install the formula directly:

```bash
$ brew install tomkyle/daily/repo-info
```

# Usage and Example

Run *repo-info* without parameters to get a short help text. 


```bash
$ repo-info vendor/project [version]
```

**version:** Version tag like `1.0.13` which is useful for homebrew taps. If omitted, `master` will be assumed.


```bash
$ repo-info slimphp/Slim 2.5.0

Repo:      slimphp/Slim <https://github.com/slimphp/Slim>
Version:   2.5.0
Tarball:   https://github.com/slimphp/Slim/archive/2.5.0.tar.gz
SHA-256:   c4c3a81b311069b0dc4ebedd7aa843e86dcb9f3938e5e6ea3e03b6e225c4a21c

The SHA-256 was copied to your clipboard. Use Cmd/Strg-V to paste somewhere.
```


                          
