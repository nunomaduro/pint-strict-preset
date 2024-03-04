<p align="center">
    <img src="https://raw.githubusercontent.com/nunomaduro/pint-strict-preset/main/art/banner.png" width="600" alt="Pint Strict Preset">
</p>

------

Pint strict preset is an insanely defensive coding style preset for those who demand meticulous precision in their projects. To use it, simply create a `pint.json` file with the following contents:

```json
{
    "preset": "laravel",
    "rules": {
        "array_push": true,
        "backtick_to_shell_exec": true,
        "declare_strict_types": true,
        "final_class": true,
        "fully_qualified_strict_types": true,
        "global_namespace_import": {
          "import_classes": true,
          "import_constants": true,
          "import_functions": true
        },
        "ordered_interfaces": true,
        "ordered_traits": true
    }
}
```
