# Week_9_lab

```bash
cd packer
```

```bash
packer init .
```

```bash
packer validate ansible.pkr.hcl
```

```bash
packer build anisble.pkr.hcl
```

## When finished packer

```bash
cd terraform
```

```bash
terraform init
```

Optional
```bash
terraform validate
```

```bash
terraform plan
```
or
```bash
terraform plan -out=file
```

```bash
terraform apply
```
or
```bash
terraform apply file
```

This will give an ip and dns when finished, go to either to see a website
