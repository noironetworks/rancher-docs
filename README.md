<h3>Version and Feature mapping between RKE, Rancher Server and ACI-CNI releases</h3>
<p>This document provides comprehensive information on the following aspects related to RKE (Rancher Kubernetes Engine), Rancher, and ACI-CNI releases:</p>

* ACI-CNI releases.

* Specific versions of RKE that first integrated each ACI-CNI release, along with the corresponding Kubernetes versions.

* All Kubernetes versions from those listed until the next listed corresponding minor versions will use the same ACI-CNI. For example, 1.25.12-rancher1-1 will use ACI-CNI 5.2.7.1.

* Initial Rancher Server version that includes an RKE version with these integrations.

* Newly introduced parameters in ACI-CNI incorporated into RKE.

<table>
  <thead>
    <tr>
      <th>ACI-CNI version</th>
      <th>acc-provision flavor</th>
      <th>Rancher version</th>
      <th>Kubernetes versions</th>
      <th>Parameters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">5.2.7.1</td>
      <td rowspan="3">RKE-1.4.6</td>
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
      <td rowspan="2">2.6.14 (RKE v1.3.24)</td>
      <td>1.24.13-rancher2-2</td>
    </tr>
    <tr>
      <td>1.23.16-rancher2-3</td>
    </tr>
    <tr>
      <td rowspan="4">6.0.3.1</td>
      <td rowspan="3">RKE-1.4.9</td>
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
      <td>2.6.14 (RKE v1.3.24)</td>
      <td>1.24.17-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="5">6.0.3.2</td>
      <td rowspan="3">RKE-1.5.3</td>
      <td rowspan="3">2.8.2* (RKE v1.5.3)</td>
      <td>1.27.8-rancher2-2</td>
      <td rowspan="5">
        <pre>kube_config:
  opflex_agent_statistics
  add_external_contract_to_default_epg
  enable_opflex_agent_reconnect
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
      <td rowspan="2">2.7.10 (RKE v1.4.13)</td>
      <td>1.26.11-rancher2-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-2</td>
    </tr>
    <tr>
      <td rowspan="6">6.0.3.3</td>
      <td rowspan="3">RKE-1.5.6</td>
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
      <td rowspan="3">2.7.13 ** (RKE v1.4.18)</td>
      <td>1.27.10-rancher1-2</td>
    </tr>
    <tr>
      <td>1.26.13-rancher1-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-3</td>
    </tr>
    <tr>
      <td rowspan="4">6.0.4.1</td>
      <td rowspan="2">RKE-1.5.6</td>
      <td rowspan="2">2.8.3 (RKE v1.5.7)</td>
      <td>1.27.11-rancher1-1</td>
      <td rowspan="4">
        <pre>kube_config:
  taint_not_ready_node
  disable_hpp_rendering
  apic_connection_retry_limit
  drop_log_disable_events
        </pre>
      </td>
    </tr>
    <tr>
      <td>1.26.14-rancher1-1</td>
    </tr>
    <tr>
      <td rowspan="2">RKE-1.4.16</td>
      <td rowspan="2">2.7.13 ** (RKE v1.4.18)</td>
      <td>1.26.11-rancher2-2</td>
    </tr>
    <tr>
      <td>1.25.16-rancher2-2</td>
    </tr>
</tbody>
</table>

<h3>Known Issue with Rancher</h3>
<p> *Rancher v2.8.2: We have identified an instability issue with Rancher v2.8.2 where variables related to ACI CNI 6032 are not being picked up by Rancher UI during cluster configuration updates or initial cluster creation.</p>
<p>** The v2.7.13 build is only available for Rancher Prime customers, through the Rancher Prime registry. </p>

## Cisco ACI and Rancher Integration Guides

- [RKE2 cluster with ACI-CNI 6.0.4.1 Installation Guide](docs/rke2-6041.md)

- [Cisco ACI and Rancher Integration with RKE 1.5.6]()
- [Cisco ACI and Rancher Integration with RKE 1.5.3]()
- [Cisco ACI and Rancher Integration with RKE 1.4.16]()
- [Cisco ACI and Rancher Integration with RKE 1.4.13]()
- [Cisco ACI and Rancher Integration with RKE 1.4.9](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-149.html)
- [Cisco ACI and Rancher Integration with RKE 1.3.24](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-1324.html)
- [Cisco ACI and Rancher Integration with RKE 1.3.13](https://www.cisco.com/c/en/us/td/docs/dcn/aci/containers/rancher-and-cisco-aci-integration/cisco-aci-and-rancher-integration-with-rke-1313.html)
