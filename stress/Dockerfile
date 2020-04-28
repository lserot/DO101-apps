FROM registry.access.redhat.com/rhscl/httpd-24-rhel7

CMD ab -dSrk -c 20 -n 50000000 http://${SCALETEST_SERVICE_HOST}:${SCALETEST_SERVICE_PORT}/index.php
