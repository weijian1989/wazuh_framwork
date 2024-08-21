# Wazuh server API

# 接口文档：

​	https://documentation.wazuh.com/current/user-manual/api/index.html#wazuh-server-api

# 简介：

The Wazuh server API is an open source RESTful API that allows interaction with the Wazuh manager from a web browser, a command-line tool such as cURL, or any script or program capable of making web requests. The Wazuh dashboard relies on the Wazuh server API to remotely manage the Wazuh server infrastructure. You can utilize the Wazuh server API to perform common tasks such as adding agents, restarting the manager(s) or agent(s), or looking up details about File Integrity Monitoring (FIM).

Here is a list of the Wazuh server API capabilities:

- Wazuh agent management
- Wazuh manager control and overview
- Cluster control and overview
- File integrity monitoring control and search
- MITRE ATT&CK and CIS-CAT overview
- Ruleset information
- Testing and verification of rules and decoders
- Syscollector information
- Role-Based Access Control (RBAC)
- API management (HTTPS, configuration)
- Users management
- Statistical information
- Error handling
- Query remote configuration

Refer to the [Wazuh server API reference](https://documentation.wazuh.com/current/user-manual/api/reference.html) for details about all the Wazuh server API endpoints. Also consider [use cases](https://documentation.wazuh.com/current/user-manual/api/use-cases.html) for example usage of the Wazuh server API.



# run and start:

```
python3 /var/ossec/api/scripts/wazuh-apid.py
```

