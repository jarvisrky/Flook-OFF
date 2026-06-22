# Security notes

flookOFF can collect network-identifying information such as switch hostnames, switchports, VLANs, management IPs, DHCP server addresses, and packet captures.

Recommended handling:

- Keep `captures/`, `sessions/`, and `exports/` out of public repos.
- Scrub exports before sharing screenshots or samples.
- Do not publish real campus switch names, management IPs, or VLAN mappings.
- Run captures only on networks where you have permission.
