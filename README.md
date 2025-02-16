# DevOps  

## Overview of Subversion and Mercurial  

### Submitted By  
**Paransh Marwari**  
500107851  
B3 (CCVT)  

### Submitted To  
**Dr. Prateek Raj Gautam**  

---

## Subversion (SVN)  

Subversion (SVN) is a version control system (VCS) designed for managing and tracking changes in source code and other files. It is centralized, meaning all versions and changes are stored in a central repository.  

### Features of SVN  
- **Centralized Repository**: A single location where all changes are stored.  
- **Version Tracking**: Maintains a history of changes for rollback or auditing.  
- **Branching and Merging**: Allows creating different development branches and merging them later.  
- **Atomic Commits**: Ensures that either all changes in a commit are applied, or none at all.  
- **Access Control**: Permissions can be managed at a granular level.  

### Advantages of SVN  
- Easier to set up for large organizations.  
- Stronger administrative control over repositories.  
- Good integration with enterprise tools.  

### Disadvantages of SVN  
- Requires a central server, making it a single point of failure.  
- Less flexible compared to distributed version control systems like Git or Mercurial.  

### Basic SVN Commands  

| Command | Description |
|---------|------------|
| `svn checkout <repo_url>` | Checkout (clone) a repository to your local machine. |
| `svn update` | Update the working copy with the latest changes from the repository. |
| `svn commit -m "message"` | Commit changes to the repository with a message. |
| `svn add <file>` | Add a new file to version control. |
| `svn delete <file>` | Remove a file from version control. |
| `svn status` | Check the status of modified files. |
| `svn log` | View commit history. |
| `svn revert <file>` | Revert changes to a specific file. |
| `svn diff` | Show differences between working copy and the latest version. |

---

## Mercurial (Hg)  

Mercurial is a distributed version control system (DVCS) designed for speed and efficiency in managing code changes. It enables developers to work offline by maintaining a full copy of the repository locally.  

### Features of Mercurial  
- **Distributed Nature**: Each user has a complete repository clone.  
- **Fast Performance**: Optimized for handling large repositories.  
- **Simple and Intuitive Commands**: Easier learning curve compared to Git.  
- **Branching and Merging**: Supports multiple development workflows.  
- **Integrity and Security**: Uses SHA-1 cryptographic hashing for file integrity.  

### Advantages of Mercurial  
- No dependency on a central server, allowing offline work.  
- Faster cloning and branching operations.  
- Easier to understand than Git for beginners.  

### Disadvantages of Mercurial  
- Less popular than Git, leading to fewer third-party integrations.  
- Larger repository sizes compared to Git due to design differences.  

### Basic Mercurial Commands  

| Command | Description |
|---------|------------|
| `hg clone <repo_url>` | Clone a repository to your local machine. |
| `hg pull` | Fetch the latest changes from a remote repository. |
| `hg update` | Apply the latest changes to your working directory. |
| `hg commit -m "message"` | Commit changes to the repository with a message. |
| `hg add <file>` | Add a new file to version control. |
| `hg remove <file>` | Remove a file from version control. |
| `hg status` | Check the status of modified files. |
| `hg log` | View commit history. |
| `hg revert <file>` | Revert changes to a specific file. |
| `hg diff` | Show differences between working copy and the latest version. |

---

### Conclusion  
Both Subversion (SVN) and Mercurial (Hg) are powerful version control systems. SVN is ideal for enterprises needing centralized control, while Mercurial provides flexibility and performance suited for distributed teams. The choice depends on the specific project requirements and team preferences.  
