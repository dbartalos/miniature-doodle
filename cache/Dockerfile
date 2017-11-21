FROM redis:latest
RUN sysctl vm.overcommit_memory=1
RUN CAT 'echo never > /sys/kernel/mm/transparent_hugepage/enabled' /etc/rc.local