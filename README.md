# Execution Environment Image Hosting

Clone this repository, download Ansible-Runner, then run:

```
ansible-builder build -f ee_image_cfg/execution-environment.yml --container-runtime=podman -c build_context --tag quay.io/rhn_sa_rhailsto/aap_ee:latest
```

commit then push to trigger build in quay.io
