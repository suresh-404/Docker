# Docker and Linux Kernel Features

Docker builds containers using **10 major system features**.  
These features come primarily from the Linux kernel and provide process isolation, security, and resource control.  

---

## Namespaces

- **PID namespace** — Isolates **process identifiers** and capabilities.  
- **UTS namespace** — Controls **host and domain names** seen by processes.  
- **MNT namespace** — Manages **filesystem access and structure** for processes.  
- **IPC namespace** — Restricts **process communication** over shared memory and message queues.  
- **NET namespace** — Provides isolated **network access and structure**.  
- **USR namespace** — Separates **user names and identifiers** inside containers from the host.  

---

## System Calls and Kernel Features

- **chroot syscall** — Changes and controls the **filesystem root** location.  
- **cgroups (Control Groups)** — Enforces **resource protection and limits** (CPU, memory, I/O, etc.).  
- **CAP drop** — Allows **dropping Linux capabilities** to restrict what processes can do.  
- **Security modules** — Provide **mandatory access controls** (e.g., SELinux, AppArmor, Seccomp).  

---

✍️ *Reference: Notes adapted from **Docker in Action***

