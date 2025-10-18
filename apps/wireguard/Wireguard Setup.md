# Wireguard Setup for UGREEN NAS
1. Go to App Center on UGOS and install Docker. Alternatively, can install Portainer or other container management software.
2. Create folders on NAS
    1. Go to Files app and navigate to docker folder
    2. Create a folder and name it "wg-easy"
    3. Create a subfolder within "wg-easy" and name it: "wireguard"
4. Docker installation
    1. Open Docker app
    2. On the left hand side, click "Project"
    3. Click "Create" button
    4. In the name field enter: "wg-easy"
    5. In the compose configuration field, paste the following [yaml file](https://raw.githubusercontent.com/EszopiCoder/ugreen-docker-guides/refs/heads/main/apps/wireguard/wg-easy-docker-compose.yaml)
    6. Click "Deploy" button
5. Portainer installation
    1. Login to Portainer
    2. On the left hande side, click "Stacks"
    3. Click "+ Add stack" button
    4. In the name field enter: "wg-easy"
    5. In the compose configuration field, paste the following [yaml file](https://raw.githubusercontent.com/EszopiCoder/ugreen-docker-guides/refs/heads/main/apps/wireguard/wg-easy-docker-compose.yaml)
    6. Click "Deploy the stack" button
6. Change router settings (Disclaimer: Every router has slightly different settings. These instructions are specific to my AT&T router: AT&T BGW320-500)
    1. Login to router
