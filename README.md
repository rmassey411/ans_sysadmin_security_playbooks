**Playbooks**

- **playbooks/zeronetworks_breakglass.yml**: [playbooks/zeronetworks_breakglass.yml](playbooks/zeronetworks_breakglass.yml#L1) — An Ansible playbook to run the Zero Networks "breakglass" process on unreachable hosts. Defines `targetNode`, `segmentServer`, `deploymentCluster`, and `mode`, then includes the `ans_zeronetworks_misc_role` task `breakglass/run_script.yml` to execute the breakglass script on the segment server.

