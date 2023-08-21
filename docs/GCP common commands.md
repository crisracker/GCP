# GCP gCloud shell Common Commands

## Check gCloud version

```cmd

gcloud --version

```

## Check gCloud Info

```cmd

gcloud info

```

## gCloud components update

```cmd

gcloud components update

```

## Check gCloud Cheatsheet

```cmd

gcloud cheatsheet

```

## Initialization gCloud

```cmd

gcloud init
gcloud init --console-only

```

## List compute instances

```cmd

gcloud compute instances list --filter=zone=us-central1-a

```

## Start compute instances

```cmd

gcloud compute instances start test-vm-01 --zone=us-central1-a

```

## Stop compute instances

```cmd

gcloud compute instances stop test-vm-01 --zone=us-central1-a

```

## Plugins for GKE

```cmd

gcloud components install gke-gcloud-auth-plugin

```

## Other gCloud settings

```cmd

(Optional) To improve the screen reader experience, enable the accessibility/screen_reader property: gcloud config set accessibility/screen_reader true

```

