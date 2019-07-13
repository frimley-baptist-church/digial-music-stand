# Digial Music Stand

### What is DMS?

DMS is a [Raspberry Pi 3 Model B Plus](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/) application that displays song lyrics retrieved from [OpenLP](https://openlp.org/) - an open-source worship presentation software application for Windows, Mac and Linux.

### OK, nice idea, but why not use the in-built OpenLP stage view?

Unfortunately, for us anyway, the OpenLP [stage view](http://manual.openlp.org/stage_view.html) doesn't operate as we'd like, hence this project.
For example, when on a particular song, and we're on page 2, the stage view removes page 1 from view entirely, all the words then move around - it's quite disconcerting as a singer needing a _whole song view_ to be able to work our where you'll go back to for repeats etc.

### The tech stack

DMS is built using the [Svelte](https://svelte.dev/) web framework. The _viewer_ part of DMS is just a web page that exploits the underlying web api that powers the [OpenLP Web Remote](http://manual.openlp.org/web_remote.html) facility. No reconfiguration of OpenLP itself is required. You just get DMS running, enter the IP address of your OpenLP computer, and everything else should _just work_.

### Why use a Raspberry Pi?

Well, because we can! Seriously, it's a cheap computer, ideal for this kind of work. The Raspberry Pi is so compact you can attach it to the back of a monitor using velcro, and have a relatively self-contained setup.

Once our project is up and running, we'll add some photos here.
