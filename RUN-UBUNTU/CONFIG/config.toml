# GitLab_CI-CD
GitLab CI/CD


config(ServerUBUNTU)
 /etc/gitlab-runner/config.toml

[[runners]]
  name = "ip-172-31-94-91"
  url = "https://gitlab.com/"
  token = "vXTyum*******35u"
  executor = "docker"
  [runners.custom_build_dir]
  [runners.docker]
    tls_verify = false
    image = "ubuntu"
    privileged = false
    disable_entrypoint_overwrite = false
    oom_kill_disable = false
    disable_cache = false
    volumes = ["/var/run/docker.sock:/var/run/docker.sock", "/cache:/cache"]
    shm_size = 0
  [runners.cache]
    [runners.cache.s3]
    [runners.cache.gcs]

