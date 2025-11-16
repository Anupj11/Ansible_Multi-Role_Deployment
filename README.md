<div align="center">

# ⚙️🚀 Automated Multi-Server Deployment with **Ansible**
### _Security • Docker • Nginx • Website Deployment_

✨ “20+ tasks, multiple roles, countless errors… but the deployment finally runs smoother than butter!” ✨
</div>

     ┌────────────────────┐
     │   Master Node 🧠   │
     └─────────┬──────────┘
               │ SSH + Ansible
               ▼
  ┌─────────────────────────────┐
  │        Worker Nodes ⚙️      │
  │  (Security + Docker + Nginx)│
  └─────────────────────────────┘
               │
               ▼
     🌐  Website Deployed ✔️








🚀 Installing Docker......... ████████████████ 100%


🛡️ Hardening SSH.............. ████████████████ 100%


🌐 Deploying Nginx............ ████████████████ 100%


📂 Copying Website Files...... ████████████████ 100%


🔥 Enabling Firewall.......... ████████████████ 100%


✨ FINAL STATUS: FAILED=0 ✨

> ⚡ Full multi-role Ansible automation  
> 🔐 Security hardening with sysctl + SSH lockdown  
> 🐳 Docker engine installation via signed-by keyrings  
> 🌐 Nginx web server deployment  
> 📄 Static website deployment  
> 🔁 Fully idempotent & production-safe  


🔍 Checking Syntax...
ansible-playbook -i /etc/ansible/hosts site.yaml --syntax-check

🚀 Running Deployment...
ansible-playbook -i /etc/ansible/hosts site.yaml

📡 Testing Server Connectivity...
ansible all -m ping


🌟 Role Breakdown
🛡️ Security Role
✔ Disable root login  
✔ Disable password SSH  
✔ Harden sysctl  
✔ Install + enable UFW  
✔ Install + enable Fail2Ban  

🐳 Docker Role
✔ Add Docker GPG key  
✔ Add Docker repo  
✔ Install Docker CE + CLI  
✔ Enable Docker service  

🌐 Nginx Role
✔ Install Nginx  
✔ Manage service  
✔ Serve static website  

📄 Website Role
✔ Create /var/www/html  
✔ Copy index.html  
✔ Set permissions  
✔ Auto-start Nginx 

What I Learned (with motion)
🌀 Debugging -vvv  
🧩 Fixing role structure issues  
🚫 Avoiding YAML indentation nightmares  
🧱 Installing missing Ansible collections  
🛡️ Understanding real-world server hardening  
🌍 Deploying across multiple EC2 worker nodes  

Future Enhancements
✨ Add SSL (Let's Encrypt)
✨ Add Load Balancer
✨ Add Terraform provisioning
✨ Add CI/CD (Jenkins or GitHub Actions)
✨ Add Monitoring (Prometheus + Grafana)

<div align="center">

## 👋 Hey, I’m **Anup Jadhav**

_Aspiring Cloud & DevOps Engineer_

🌐 Let’s Connect & Build Together
</div>
🌟 LinkedIn: 
👉 https://www.linkedin.com/in/anup-jadhav/

📧 Email:
👉 jadhavanup15@gmail.com

❤️ Thank You for Visiting This Repository
If my project helped or inspired you, a ⭐ STAR would mean a lot!


