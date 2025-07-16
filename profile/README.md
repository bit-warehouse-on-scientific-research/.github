# Guidelines

## 1. Repository Structure

Please organize your repository following the directory structure below:
```
Repository of Research Paper/
├── code (required)/
│ ├── README.md
│ ├── result/
│ ├── ...
│ └── dataset (optional)/
├── paper (required)/
│ ├── tex (required, LaTeX source file)/
│ ├── ...
│ ├── .* (optional, response/rebuttal records in any format)
│ └── .pdf (optional)
├── docker (optional)/
│ ├── Dockerfile
│ └── README.md
└── README.md (optional)
```
### Details for Each Folder:
- **`code/`**  
  This folder should include the source code, results, and dataset (if any) related to your paper. If your paper generates a dataset as part of its proposed methodology, you must upload the essential dataset here. Additionally, a `README.md` file is required to provide clear instructions for reproducing the experiments described in your paper.  

- **`paper/`**  
  This folder should contain the compiled paper files, preferably in LaTeX. Optionally, you can include a `.pdf` version of the paper and records of responses or rebuttals any format.  

- **`docker/`**  
  If your experiments rely on Docker, include the necessary `Dockerfile` and a `README.md` with instructions for building and running the Docker container.  


## 2. Repository Permissions

Ensure the repository permissions are set to allow access for your team members. 
