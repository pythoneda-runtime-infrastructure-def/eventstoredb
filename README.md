# pythoneda-runtime-infrastructure/eventstoredb

This is the definition for [https://github.com/pythoneda-runtime-infrastructure/eventstoredb](https://github.com/pythoneda-runtime-infrastructure/eventstoredb "pythoneda-runtime-infrastructure/eventstoredb").

## How to declare it in your flake

Check the latest tag of this repository and use it instead of the `[version]` placeholder below.

```nix
{
  description = "[..]";
  inputs = rec {
    [..]
    pythoneda-runtime-infrastructure-eventstoredb = {
      [optional follows]
      url =
        "github:pythoneda-runtime-infrastructure-def/eventstoredb/[version]";
    };
  };
  outputs = [..]
};
```

Should you use another PythonEDA modules, you might want to pin those also used by this project. The same applies to [nixpkgs](https://github.com/nixos/nixpkgs "nixpkgs") and [flake-utils](https://github.com/numtide/flake-utils "flake-utils").

Use the specific package depending on your system (one of `flake-utils.lib.defaultSystems`) and Python version:

- `#packages.[system].pythoneda-runtime-infrastructure-eventstoredb-python38` 
- `#packages.[system].pythoneda-runtime-infrastructure-eventstoredb-python39` 
- `#packages.[system].pythoneda-runtime-infrastructure-eventstoredb-python310` 
- `#packages.[system].pythoneda-runtime-infrastructure-eventstoredb-python311` 
