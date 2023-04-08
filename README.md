# Houdini MLOPs
Machine Learning Plugin for Houdini developed by Ambrosiussen Holding and Entagma, Licensed and Distributed by Bismuth Consultancy BV.

Paul Ambrosiussen:

[![](https://img.shields.io/badge/twitter-%230077B5.svg?style=for-the-badge&logo=twitter)](https://twitter.com/ambrosiussen_p)
[![](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/paulambrosiussen/)

Entagma:

[![](https://img.shields.io/badge/twitter-%230077B5.svg?style=for-the-badge&logo=twitter)](https://twitter.com/entagma)

You can join the Discord to chat about the plugin: https://discord.gg/rKr5SNZJtM

By downloading or using the plugin (or any of its contents), you are agreeing to the LICENSE found in this repository and [Terms of Service of Bismuth Consultancy B.V.](https://www.bismuthconsultancy.com/s/EN_Terms_And_Conditions-f5sk.pdf)

Please note that the plugin is currently in beta, and may change at anytime without notice.

# Installing for Houdini
To install the plugin for the first time, follow these steps:
1. Clone this repository and make note of the directory you have cloned it to.
2. Copy the `MLOPs.json` file found in the repository root, and paste it in the $HOUDINI_USER_PREF_DIR/packages/ folder.
3. Edit the `MLOPs.json` file you just pasted, and modify the `$MLOPS` path found inside. Set the path to where you cloned the repository to in step one.
# Download your preferred Stable Diffusion model, e.g.:
4. Create a folder where you want the model to be stored. make sure to have enough free space. Models can be huge.
5. Make sure you have git installed.
6. Open a command prompt, go to the subfolder you just created.
now enter these commands:
7. git lfs
8. git clone "https://huggingface.co/stabilityai/stable-diffusion-2-1"
9. Wait. Grab a coffee. Watch "Das Boot". Plant a tree...
10. Launch Houdini and open the `MLOPs` shelf. Click the `Install` shelf button. Restart Houdini once complete. If you are experiencing any issues in this step please see the troubleshooting section. (CONTACT US!)
11. In the MLOPs nodes, set Model Cache to Disk and then select the SD model's folder you just cloned
