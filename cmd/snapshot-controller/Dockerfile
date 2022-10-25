FROM cr.loongnix.cn/library/alpine:3.11
LABEL maintainers="qiangxuhui@loongson.cn"
LABEL description="Snapshot Controller"
ARG binary=./bin/snapshot-controller

COPY ${binary} snapshot-controller
ENTRYPOINT ["/snapshot-controller"]
