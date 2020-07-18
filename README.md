# Bugfixed

# Fix info grafana from dockprom

Fixed by running -

mount -o remount,rw '/sys/fs/cgroup'
ln -s /sys/fs/cgroup/cpu,cpuacct /sys/fs/cgroup/cpuacct,cpu
