# assets

Asset bank for hosting files with stable URLs.

> [!IMPORTANT]
> Keep this repo **public** and **accessible**.  
> External projects reference these assets.

## Usage

Organise assets into named directories, one per project.  
Assets spanning more than one project go under `global/`.

```sh
assets/
├── global/      # shared assets
│   └── logo.svg
├── foo/         # a project
│   ├── foo.png  # an asset
│   └── bar.svg
└── bar/         
    └── baz.pdf  

# ... and so on
```

### Add a project

GitHub cannot commit an empty directory,    
so seed it with a `.gitkeep` placeholder.

1. Click `Add file` → `Create new file`.
2. Set the path to `assets/<name>/.gitkeep`.
3. Click `Commit changes` to commit to `main`.

### Upload an asset

1. Open the target directory.
2. Click `Add file` → `Upload files`.
3. Upload the file, then commit.

### Copy an asset URL

1. Open the asset in the Web UI.
2. Right-click the asset.
3. Click `Copy image address` for images, or `Copy link` otherwise.

## License

Unless stated otherwise, all assets are proprietary   
and owned by their respective authors
