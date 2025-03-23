## Day 3 - ELK Stack and Filebeat Logs Setup

### ELK Stack Deployment
- Deployed ELK Stack (Elasticsearch, Logstash, Kibana) on a new Virtual Machine (VM).
- Configured Elasticsearch to store and index log data.
- Set up Logstash to process and route incoming logs.
- Enabled Kibana to visualize and analyze collected logs.

### Filebeat Logs Configuration
- Installed and configured **Filebeat** on multiple VMs to forward logs to the ELK server.
- Defined input sources and log paths for each VM.
- Verified successful log transmission by checking Elasticsearch indices and Kibana dashboards.

### VM Network Configuration
- Configured network settings to allow seamless communication between:
  - ELK VM
  - Application VMs in the DMZ and Internal Subnets
- Ensured that logs from all VMs are properly routed to the ELK stack.

### Verification and Testing
- Tested the entire logging pipeline to ensure data consistency and correctness.
- Verified Kibana dashboards to confirm log ingestion and visualization.

