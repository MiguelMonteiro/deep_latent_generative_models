# deep_latent_generative_models
A Tutorial on deep latent variable generative models

## Installation

You can always install manually with `python3 -m venv venv`, `source venv/bin/activate`, and `pip install -r requirements.txt`. We include a Dockerfile and VSCode devcontainer for convenience. The instructions below show two convenient ways to install everything.


### Option 1: Use VSCode Remote Containers

```bash
git clone https://github.com/Charl-AI/ml_basics.git
cd ml_basics
```

Check that your Docker installation is working:

```bash
docker run hello-world
```

If you use VSCode with the remote containers extension, you can install the dependencies and open a VSCode development environment for this project by simply running `Remote Containers: Open folder in Container` from the command palette. You can then run any project you want by pasting the run command into the integrated terminal.

### Option 2: Codespaces!

(New as of Nov 2022: GitHub provides a free tier with 80 hours per month of compute.)

You can open this repo **without any local installation** in a cloud-hosted 'codespace'. The dependencies will be automatically installed on the remote cloud machine, which you can access through your browser, VSCode, or even PyCharm. Simply start the codespace using the button in the GitHub UI. This is the easiest way to try out this project.
