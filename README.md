# Dev-D7: Monitor System Resources Using Netdata (Ubuntu EC2 + Docker)

# Objective
Monitor system and application metrics using Netdata, deployed via Docker on an Ubuntu EC2 server.

# Tools
- Ubuntu EC2 (AWS)
- Docker
- Netdata
- GitHub

# 🔧 Steps

1. Launched Ubuntu EC2 and installed Docker.
2. Ran Netdata:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
3.Opened port 19999 in EC2 Security Group.

4.Accessed dashboard: http://<EC2-IP>:19999
