# Example Plugin with Only Markdown Files

Modify this plugin to create your own plugin:
1. Edit `pyproject.toml` and replace `aimsh_sample_plugin` with the name of your plugin.  Note: all plugins must begin with `aimsh_` because this is how the plugin system identifies relevant packages.
  - The plugin name must appear in the `name` field under `[project]` and it must also appear under `[tool.setuptools.package-data]` to include the markdown files as resources.
  - Optional, but recommended: add description, author, and modify README to reflect your plugin information
2. Rename the folder `aimsh_sample_plugin` to the name of your plugin.
3. Remove the sample markdown files and include your own
4. Note, you must retain the empty file `__init__.py` because this establishes a module.
  - Leave the file empty and do not add any other Python files.  This ensures the package is safe and contains no malicious code.

