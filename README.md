[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ruivieira/trustyai-binder/HEAD)

# trustyai-binder

A template for Java-based TrustyAI Jupyter notebooks.

## Usage

- Press [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ruivieira/trustyai-binder/HEAD)
- Select the `explainability-core-example.ipynb` notebook

### Shell commands

Shell commands are disabled by default from within the Jupyter notebook. To enable them, from a code cell run:

```java
import io.github.spencerpark.ijava.IJava;
import io.github.spencerpark.jupyter.kernel.magic.common.Shell;
IJava.getKernelInstance().getMagics().registerMagics(Shell.class);
```

The `%sh` magic is now available. As an example to download a file:

```
%sh wget https://...
```

## Template

- Clone this repository (or use it as a Github template)
- Change the above Binder badge so it points to your new repository (or use the URL directly from Binder)
- Happy coding!

## Contributing

Please add any comments, feedback or bugs using the [issues](https://github.com/ruivieira/trustyai-binder/issues).

PRs welcome!
