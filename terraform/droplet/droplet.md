# How to provision a droplet

```bash
terraform plan \
  -var "do_token=${DO_PAT}" \
  -var "pvt_key=$HOME/.ssh/id_ed25519"
```
