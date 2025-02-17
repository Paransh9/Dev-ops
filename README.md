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

### Basic SVN Commands with Examples  

| Command | Description | Example |
|---------|------------|---------|
| `svn checkout <repo_url>` | Checkout (clone) a repository to your local machine. | `svn checkout https://example.com/svn/project` |
| `svn update` | Update the working copy with the latest changes from the repository. | `svn update` |
| `svn commit -m "message"` | Commit changes to the repository with a message. | `svn commit -m "Fixed login bug"` |
| `svn add <file>` | Add a new file to version control. | `svn add index.html` |
| `svn delete <file>` | Remove a file from version control. | `svn delete old_script.py` |
| `svn status` | Check the status of modified files. | `svn status` |
| `svn log` | View commit history. | `svn log` |
| `svn revert <file>` | Revert changes to a specific file. | `svn revert main.css` |
| `svn diff` | Show differences between working copy and the latest version. | `svn diff script.js` |

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

### Basic Mercurial Commands with Examples  

| Command | Description | Example |
|---------|------------|---------|
| `hg clone <repo_url>` | Clone a repository to your local machine. | `hg clone https://example.com/hg/project` |
| `hg pull` | Fetch the latest changes from a remote repository. | `hg pull` |
| `hg update` | Apply the latest changes to your working directory. | `hg update` |
| `hg commit -m "message"` | Commit changes to the repository with a message. | `hg commit -m "Updated homepage UI"` |
| `hg add <file>` | Add a new file to version control. | `hg add about.html` |
| `hg remove <file>` | Remove a file from version control. | `hg remove old_style.css` |
| `hg status` | Check the status of modified files. | `hg status` |
| `hg log` | View commit history. | `hg log` |
| `hg revert <file>` | Revert changes to a specific file. | `hg revert config.json` |
| `hg diff` | Show differences between working copy and the latest version. | `hg diff app.js` |

---

### Conclusion  
Both Subversion (SVN) and Mercurial (Hg) are powerful version control systems. SVN is ideal for enterprises needing centralized control, while Mercurial provides flexibility and performance suited for distributed teams. The choice depends on the specific project requirements and team preferences.  
