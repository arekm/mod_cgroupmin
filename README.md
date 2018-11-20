Minimalistic mod_cgroup.
========================

Changes compared to mod_cgroup:
- dropped dependency on libcgroup (which doesn't handle cgroup v2)
- use arbitrary group names
- work nicely with mod_apparmor (dependencies order)
