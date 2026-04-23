## 🖼️ Architecture Diagram

![Architecture](screenshots/architecture.png)

## 🚀 How to Deploy

```bash
terraform init
terraform validate
terraform plan
terraform apply


---

# ⚔️ STEP 4: Add Real Explanation (THIS IS DIFFERENTIATOR)

Add this in README:

```markdown
## 🧠 Key Design Decisions

- Used private subnet for EC2 to enhance security
- Implemented NAT Gateway for outbound internet access
- Used ALB to distribute traffic across instances
- Configured Auto Scaling for high availability