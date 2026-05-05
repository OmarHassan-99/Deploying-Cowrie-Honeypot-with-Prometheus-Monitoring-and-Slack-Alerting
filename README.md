# Deploying-Cowrie-Honeypot-with-Prometheus-Monitoring-and-Slack-Alerting

This lab documentation details the deployment and advanced configuration of 
a Cowrie honeypot designed to log brute-force attacks and malicious shell 
interactions. It outlines the transition from a basic installation to a 
highly realistic deception environment by customizing the virtual 
filesystem, adjusting user credentials, modifying the hostname, and spoofing 
the MAC address to evade anti-virtualization techniques. Additionally, the 
lab covers the containerization of the monitoring stack using Docker, 
successfully integrating Cowrie with Prometheus, Node Exporter, and cAdvisor 
to continuously track both system and container-level metrics. Finally, it 
demonstrates the configuration of Alertmanager to trigger and send real-time 
notifications directly to a Slack channel whenever specific malicious 
activities, such as brute-force attempts or unauthorized command executions, 
are detected within the honeypot.  



