# Project Name
This project is ________. (Describe the main goals of the project. Limit to 1-2 sentences)

## Description
Optional section to provide a more detailed overview of the project.

## Get Started
This section should be used to summarize the project and how to get started after cloning. Once this section 
is edited, it will show up on the Project Dashboard tab. 

If you completely delete this section, the "Get Started" widget will be removed from the Project Dashboard.

Hello README!
mkdir -p $HOME/.nvwb/bin && \
curl -L https://workbench.download.nvidia.com/stable/workbench-cli/$(curl -L -s https://workbench.download.nvidia.com/stable/workbench-cli/LATEST)/nvwb-cli-$(uname)-$(uname -m) --output $HOME/.nvwb/bin/nvwb-cli && \
chmod +x $HOME/.nvwb/bin/nvwb-cli && \
sudo -E $HOME/.nvwb/bin/nvwb-cli install
