# Cosxl docker

Dockerization of the [Hugging Face Cosxl Space](https://huggingface.co/spaces/multimodalart/cosxl)

 * Space: [multimodalart/cosxl](https://huggingface.co/spaces/multimodalart/cosxl)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

You can download the image and run it

```bash
docker pull maximofn/cosxl:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```