# Jupyter-Spigot
Minecraft Server Spigot Build, update and run


{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Minecraft server\n",
    "\n",
    "- erstelle mit java -jar BuildTools.jar\n",
    "- cp spiegot.jar server/spiegot.jar \n",
    "- starte mit java -jar -Xmx2048M spigot.jar"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "cd\n",
    "mkdir -p minecraft/server\n",
    "cd minecraft"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "wget https://hub.spigotmc.org/jenkins/job/BuildTools/71/artifact/target/BuildTools.jar"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "cd /home/wipf/minecraft\n",
    "java -jar BuildTools.jar"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "mv  spigot-1.12.2.jar spigot.jar"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "cp spigot.jar server/spigot.jar "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "cd /home/wipf/minecraft/server\n",
    "java -jar -Xmx2048M spigot.jar"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Bash",
   "language": "bash",
   "name": "bash"
  },
  "language_info": {
   "codemirror_mode": "shell",
   "file_extension": ".sh",
   "mimetype": "text/x-sh",
   "name": "bash"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
