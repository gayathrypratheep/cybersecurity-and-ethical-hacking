# Linux Cheatsheet (Cybersecurity Foundations)

---

## File System Navigation
| Command | What it does | Example |
|---------|--------------|---------|
| `pwd`   | Show current directory | `pwd → /home/kali` |
| `ls`    | List files | `ls -l` (detailed), `ls -a` (hidden files) |
| `cd dir` | Change directory | `cd /etc` |
| `cd ..` | Go up one directory | `cd ..` |
| `cd ~`  | Go to home directory | `cd ~` |

---

## File & Directory Permissions
| Command | What it does | Example |
|---------|--------------|---------|
| `ls -l` | Show permissions | `-rwxr-xr-- file.txt` |
| `chmod` | Change permissions | `chmod 755 script.sh` (rwxr-xr-x) |
| `chown` | Change owner | `sudo chown root:root file.txt` |
| `stat file` | Detailed file info | `stat file.txt` |

---

##  Package Management (Debian/Kali)
| Command | What it does | Example |
|---------|--------------|---------|
| `sudo apt update` | Refresh package list | – |
| `sudo apt upgrade` | Upgrade all installed packages | – |
| `sudo apt install pkg` | Install package | `sudo apt install nmap` |
| `sudo apt remove pkg` | Remove package | `sudo apt remove nmap` |
| `dpkg -i file.deb` | Install `.deb` file | `sudo dpkg -i tool.deb` |
| `dpkg -l` | List installed packages | `dpkg -l | grep nmap` |

---

##  Networking Commands
| Command | What it does | Example |
|---------|--------------|---------|
| `ifconfig` / `ip a` | Show network interfaces & IPs | `ip a` |
| `ping host` | Test connectivity | `ping -c 4 google.com` |
| `netstat -tuln` | Show open ports/services | `sudo netstat -tuln` |
| `ss -tuln` | Modern replacement for netstat | `sudo ss -tuln` |
| `traceroute host` | Show path packets take | `traceroute google.com` |

---

