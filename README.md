# MkDocs Material Devcontainer

To be able to use the live preview of mkdocs via GitHub Codespaces, you must release the standard port 8000. So that you don't have to do this manually, you can also create a `devcontainer/devcontainer.json` and write the configuration into it. This configuration will be used automatically when you create a new devcontainer.

After that you can execute `mkdocs serve` in the terminal to start the live preview.

This is what the project structure of my simple documentation looks like:

```
.
├── README.md
├── docs
│ └─── index.md
├── mkdocs.yml
└── requirements.txt

2 directories, 4 files
```