FROM registry.redhat.io/ansible-tower-37/ansible-tower-rhel7

ADD ./assets/launch_awx.sh /usr/bin/launch_awx.sh

ENTRYPOINT ["tini", "--"]
CMD /usr/bin/launch_awx.sh