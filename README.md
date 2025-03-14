<table>
  <thead>
    <tr>
      <th>ACI-CNI version</th>
      <th>acc-provision flavor</th>
      <th>RKE version</th>
      <th>Rancher version</th>
      <th>Kubernetes versions</th>
      <th>Parameters</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td rowspan="5">6.1.1.2</td>
      <td rowspan="3">RKE-1.7.2</td>
      <td rowspan="3">1.7.2</td>
      <td rowspan="3">2.10.2 (RKE v1.7.2)</td>
      <td>1.31.4-rancher1-1</td>
      <td rowspan="5">
        <pre>
kube_config:
  proactive_conf
        </pre>
      </td>
    </tr>
    <tr>
    <td> 1.30.8-rancher1-1</td>
    </tr>
    <tr>
    <td> 1.29.12-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.6.6</td>
      <td rowspan="2">1.6.6</td>
      <td rowspan="2">2.9.6 (RKE v1.6.6)</td>
      <td>1.30.8-rancher1-1</td>
    </tr>
    <tr>
      <td>1.29.12-rancher1-1</td>
    </tr>
        <tr>
      <td rowspan="5">6.0.4.4<sup>1</sup></td>
      <td rowspan="3">RKE-1.7.1</td>
      <td rowspan="3">1.7.1</td>
      <td rowspan="3">2.10.1 (RKE v1.7.1)</td>
      <td>1.31.3-rancher1-1</td>
      <td rowspan="5">
        <pre>
drop_log_config:
  opflex_redirect_drop_logs
        </pre>
      </td>
    </tr>
    <tr>
    <td> 1.30.7-rancher1-1</td>
    </tr>
    <tr>
    <td> 1.29.11-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.6.5</td>
      <td rowspan="2">1.6.5</td>
      <td rowspan="2">2.9.5 (RKE v1.6.5)</td>
      <td>1.30.7-rancher1-1</td>
    </tr>
    <tr>
      <td>1.29.11-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="4">6.1.1.1</td>
      <td rowspan="3">RKE-1.6.3</td>
      <td rowspan="3">1.6.3</td>
      <td rowspan="3">2.9.3 (RKE v1.6.3)</td>
      <td>1.30.5-rancher1-1</td>
      <td rowspan="4">
        <pre>kube_config:
  enable_hpp_direct
  opflex_agent_reset_wait_delay
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.29.9-rancher1-1</td>
    </tr>
    <tr>
      <td>1.28.14-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="1">RKE-1.5.14</td>
      <td rowspan="1">1.5.14</td>
      <td rowspan="1">2.8.9 (RKE v1.5.14)</td>
      <td>1.28.14-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="4">6.0.4.3</td>
      <td rowspan="3">RKE-1.6.2</td>
      <td rowspan="3">1.6.2</td>
      <td rowspan="3">2.9.2 (RKE v1.6.2)</td>
      <td>1.30.4-rancher1-1</td>
      <td rowspan="4">
        <pre>kube_config:
  unknown_mac_unicast_action
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.29.8-rancher1-1</td>
    </tr>
    <tr>
      <td>1.28.13-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="1">RKE-1.5.13</td>
      <td rowspan="1">1.5.13</td>
      <td rowspan="1">2.8.8 (RKE v1.5.13)</td>
      <td>1.28.13-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="7">6.0.4.2</td>
      <td rowspan="4">RKE-1.6.0</td>
      <td rowspan="4">1.6.0</td>
      <td rowspan="4">2.9.1 (RKE v1.6.1)</td>
      <td>1.30.2-rancher1-1</td>
      <td rowspan="7">
        <pre>kube_config:
  opflex_startup_enabled       
  opflex_startup_policy_duration
  opflex_startup_resolve_aftConn
  opflex_switch_sync_delay      
  opflex_switch_sync_dynamic
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.29.6-rancher1-1</td>
    </tr>
    <tr>
      <td>1.28.11-rancher1-1</td>
    </tr>
    <tr>
      <td>1.27.15-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.5.11</td>
      <td rowspan="2">1.5.11</td>
      <td rowspan="2">2.8.6 (RKE v1.5.11)</td>
      <td>1.28.11-rancher1-1</td>
    </tr>
    <tr>
      <td>1.27.15-rancher1-1</td>
    </tr>
    <tr>
      <td>RKE-1.4.20</td>
      <td>1.4.20</td>
      <td>2.7.15 (RKE v1.4.20)</td>
      <td>1.27.15-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="4">6.0.4.1</td>
      <td rowspan="2">RKE-1.5.6</td>
      <td rowspan="2">1.5.6</td>
      <td rowspan="2">2.8.3 (RKE v1.5.7)</td>
      <td>1.27.11-rancher1-1</td>
      <td rowspan="4">
        <pre>kube_config:
  taint_not_ready_node
  disable_hpp_rendering
  apic_connection_retry_limit
drop_log_config:
  disable_events
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.26.14-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.4.16</td>
      <td rowspan="2">1.4.16</td>
      <td rowspan="2">2.7.13 (RKE v1.4.18)</td>
      <td>1.27.11-rancher1-1</td>
    </tr>
    <tr>
      <td>1.26.14-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="6">6.0.3.3</td>
      <td rowspan="3">RKE-1.5.6</td>
      <td rowspan="3">1.5.6</td>
      <td rowspan="3">2.8.3 (RKE v1.5.7)</td>
      <td>1.27.10-rancher1-2</td>
      <td rowspan="6">
        <pre>
  none
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.26.13-rancher1-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-3</td>
    </tr>
    <tr>
      <td rowspan="3">RKE-1.4.16</td>
      <td rowspan="3">1.4.16</td>
      <td rowspan="3">2.7.13 (RKE v1.4.18)</td>
      <td>1.27.10-rancher1-2</td>
    </tr>
    <tr>
      <td>1.26.13-rancher1-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-3</td>
    </tr>
    <tr>
      <td rowspan="5">6.0.3.2</td>
      <td rowspan="3">RKE-1.5.3</td>
      <td rowspan="3">1.5.3</td>
      <td rowspan="3">2.8.2* (RKE v1.5.3)</td>
      <td>1.27.8-rancher2-2</td>
      <td rowspan="5">
        <pre>kube_config:
  opflex_agent_statistics
  add_external_contract_to_default_epg
  enable_opflex_agent_reconnect**
  opflex_openssl_compat
  node_snat_redirect_exclude
  toleration_seconds
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.26.11-rancher2-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-2</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.4.13</td>
      <td rowspan="2">1.4.13</td>
      <td rowspan="2">2.7.10 (RKE v1.4.13)</td>
      <td>1.26.11-rancher2-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-2</td>
    </tr>
    <tr>
      <td rowspan="4">6.0.3.1</td>
      <td rowspan="3">RKE-1.4.9</td>
      <td rowspan="3">1.4.9</td>
      <td rowspan="3">2.7.9 (RKE  v1.4.10)</td>
      <td>1.26.8-rancher1-1</td>
      <td rowspan="4">
        <pre>kube_config:
  use_system_node_priority_class
  ovs_memory_request
  aci_containers_controller_memory_limit
  aci_containers_controller_memory_request
  aci_containers_host_memory_limit
  aci_containers_host_memory_request
  mcast_daemon_memory_limit
  mcast_daemon_memory_request
  opflex_agent_memory_limit
  opflex_agent_memory_request
  aci_containers_memory_limit
  aci_containers_memory_request
  opflex_device_reconnect_wait_timeout
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.25.13-rancher1-1</td>
    </tr>
    <tr>
      <td>1.24.17-rancher1-1</td>
    </tr>
    <tr>
      <td>RKE-1.3.24</td>
      <td>1.3.24</td>
      <td>2.6.14 (RKE v1.3.24)</td>
      <td>1.24.17-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="5">5.2.7.1</td>
      <td rowspan="3">RKE-1.4.6</td>
      <td rowspan="3">1.4.6</td>
      <td rowspan="3">2.7.6 (RKE  v1.4.8)</td>
      <td>1.26.4-rancher2-1</td>
      <td rowspan="5">
        <pre>kube_config:
  opflex_agent_policy_retry_delay_timer
  aci_multipod
  aci_multipod_ubuntu
  dhcp_renew_max_retry_count
  dhcp_delay
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.25.9-rancher2-2</td>
    </tr>
    <tr>
      <td>1.24.13-rancher2-2</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.3.21</td>
      <td rowspan="2">1.3.21</td>
      <td rowspan="2">2.6.14 (RKE v1.3.24)</td>
      <td>1.24.13-rancher2-2</td>
    </tr>
    <tr>
      <td>1.23.16-rancher2-3</td>
    </tr>
</tbody>
</table>

> **&#9432;** ___NOTE:___
>
>  <sup>1</sup> Downgrading ACI-CNI from version 6.1.1.1 to 6.0.4.4 is not supported. Therefore, if you are currently using ACI-CNI 6.1.1.1, avoid upgrading to RKE Kubernetes versions associated with 6.0.4.4.

This table provides information on the following aspects related to RKE (Rancher Kubernetes Engine), Rancher, and ACI-CNI releases:

* ACI-CNI releases.

* Specific versions of RKE that first integrated each ACI-CNI release, along with the corresponding Kubernetes versions.

    > Note: All Kubernetes versions from those listed until the next listed corresponding minor versions will use the same ACI-CNI. For example, 1.25.12-rancher1-1 will use ACI-CNI 5.2.7.1..

* Initial Rancher Server version that includes an RKE version with these integrations.

* Newly introduced parameters in ACI-CNI incorporated into RKE.

---

### Known Issues
\* Rancher v2.8.2: We have identified an instability issue with Rancher v2.8.2 where variables related to ACI CNI 6032 are not being picked up by Rancher UI during cluster configuration updates or initial cluster creation.

**Resolved version:** Rancher `v2.8.4`

** Issue with `enable_opflex_agent_reconnect` flag: In versions from 6.0.3.2 till 6.0.4.2, after enabling the flag, the `"enable-opflex-agent-reconnect": true` field needs to the added manually to the controller-config for the feature to work as expected.
```bash
# edit config map to add the field under controller-config
kubectl edit cm -n aci-containers-system aci-containers-config
# restart controller pod for it to take effect
kubectl delete po -n aci-containers-system aci-containers-controller
```
after edit, the controller-config would look like this:
```yaml
controller-config:
{
    "log-level": "debug",
    "enable-opflex-agent-reconnect": true, # Added field
    "apic-hosts": ["10.30.120.180"],
    ...
}
```

**Resolved version:** ACI-CNI `v6.0.4.3`


## Cisco ACI and Rancher Integration Guides

- [RKE2 cluster with ACI-CNI 6.1.1.2 Installation Guide](docs/rke2-install.md)
- [RKE2 cluster with ACI-CNI 6.0.4.4 Installation Guide](docs/rke2-install.md)

- [Cisco ACI and Rancher Integration with RKE 1.6.3]()
- [Cisco ACI and Rancher Integration with RKE 1.6.2]()
- [Cisco ACI and Rancher Integration with RKE 1.6.0]()
- [Cisco ACI and Rancher Integration with RKE 1.5.14]()
- [Cisco ACI and Rancher Integration with RKE 1.5.13]()
- [Cisco ACI and Rancher Integration with RKE 1.5.11]()
- [Cisco ACI and Rancher Integration with RKE 1.5.6](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-rke-156.html)
- [Cisco ACI and Rancher Integration with RKE 1.5.3](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-rke-153.html)
- [Cisco ACI and Rancher Integration with RKE 1.4.20]()
- [Cisco ACI and Rancher Integration with RKE 1.4.16](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-rke-1416.html)
- [Cisco ACI and Rancher Integration with RKE 1.4.13](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-rke-1413.html)
- [Cisco ACI and Rancher Integration with RKE 1.4.9](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-149.html)
- [Cisco ACI and Rancher Integration with RKE 1.3.24](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-1324.html)
- [Cisco ACI and Rancher Integration with RKE 1.3.13](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-1313.html)