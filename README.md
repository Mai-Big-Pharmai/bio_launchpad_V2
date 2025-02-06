# Bio_Launchpad_V2

### Description
Documentation website for Big Pharmai BADDIE framework going over used libraries and AI/ML approaches.

## Installation
Clone Github repository [here](https://github.com/Mai-Big-Pharmai/bio_launchpad_V2)

##### SSH connection
```bash
git clone git@github.com:Mai-Big-Pharmai/bio_launchpad_V2.git
```

## Start Streamlit Server Locally on Digital Ocean
 - ssh into digital ocean droplet
 - navigate into bio_launchpad_v2/ directory
 - run the following command to start server
    ```bash
    streamlit run bio_launchpad_v2.py --server.port 443 --server.sslCert /root/ssl-cert/ssl/cert.pem --server.sslKeyfile /root/ssl-cert/ssl/privatekey.pem --server.headless true
    ```

## Dependencies
##### Python Packages Used
 - streamlit
 - pillow