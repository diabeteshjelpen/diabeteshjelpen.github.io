# diabeteshjelpen.github.io

[https://github.com/diabeteshjelpen/diabeteshjelpen.github.io](https://diabeteshjelpen.github.io/)

```bash
export SITE_PATH=example-site

# Create new site
hugo new site ${SITE_PATH} --format yaml

# Enter site-folder
cd ${SITE_PATH}

# Add theme
git submodule add --depth=1 https://github.com/sbruder/spectral.git themes/spectral

# Start site (dev)
hugo server --bind 0.0.0.0 -D -s .
```

## Tools

  * https://code.visualstudio.com/docs/devcontainers/tutorial
  * https://containers.dev/implementors/json_reference/
  * https://github.com/sbruder/spectral
