# Getting Started with Rasa
### Create Environment
- Create a virtual Environment using Anaconda. [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- Create a new environment named bot, install Python 3.7: `conda create --name bot python=3.7`
- Once installed, activate the environment using: `conda activate bot`

### Install Rasa Open Source
- Once the environment is activated, now you can install rasa.
- First make sure your pip version is up to date: `pip3 install -U pip`
- To install Rasa Open Source: `pip3 install rasa`

### You can now create a new project with:
- `rasa init`
- Once you will run the above command it will ask `Please enter a path where the project will be created [default: current directory]`. Enter the desired path or simply just press enter. Then you will see a directory is created at desired location.

    ![](/home/bavalpreet/../../assets/folderStructure.png)

- Then it will ask ` Do you want to train an initial model? 💪🏽 (Y/n) ` just simply press Y or if you choose to press N then later on you can train the model using **`rasa train`** command.
- Once the training is complete you can run the agent using `rasa shell` and start having conversation.

    ![](/home/bavalpreet/../../assets/output.png)