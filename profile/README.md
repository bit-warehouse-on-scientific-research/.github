# Guidelines

## 1. Repository Structure

Please organize your repository following the directory structure below:
```
Repository of Research Paper/
├── code (required)/
│ ├── README.md
│ ├── ...
│ └── result/
├── paper (required)/
│ ├── tex (required, LaTeX source file)/
│ ├── ...
│ ├── .* (optional, response/rebuttal records in any format)
│ └── .pdf (optional)
├── docker (optional)/
│ ├── Dockerfile
│ └── README.md
├── dataset (optional)/
└── README.md (optional)
```
### Details for Each Folder:
- **`code/`**  
  This folder should include the source code and results related to your paper. Additionally, a `README.md` file is required to provide clear instructions for reproducing the experiments described in your paper.  

- **`paper/`**  
  This folder should contain the compiled paper files, preferably in LaTeX. Optionally, you can include a `.pdf` version of the paper and records of responses or rebuttals any format.  

- **`docker/`**  
  If your experiments rely on Docker, include the necessary `Dockerfile` and a `README.md` with instructions for building and running the Docker container.
- **`dataset/`**
  This folder should include the dataset related to your paper. Additionally, if your paper generates a dataset as part of its proposed methodology, you must upload the essential dataset here.


## 2. Repository Permissions

Ensure the repository permissions are set to allow access for your team members. 

