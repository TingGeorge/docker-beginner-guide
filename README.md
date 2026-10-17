# 🐳 Docker for Beginners: A Visual Guide

**English** | [繁體中文](README.zh-TW.md)

> Learn Docker Desktop from scratch: install it, run your first container, host a web server, and finally start several containers at once with Compose.

### 👉 [Read the guide online](https://tinggeorge.github.io/docker-beginner-guide/)

Nothing to install, just open the link. Every step comes with screenshots and animations, so you can follow along.

---

## 📦 What problem does Docker solve?

"But it works on my machine!" It usually breaks because another computer has different versions installed.
Docker packages **your app together with everything it needs**, so it runs the same on any computer.

The two words you need to know:

- **Image**: a recipe. It's read-only and built in layers.
- **Container**: a running copy made from that recipe. One recipe can make many copies.

![An image is the recipe, a container is a running copy of it](images/image-vs-container.webp)

Containers share one Linux kernel, so they're much lighter than virtual machines:

![Containers vs virtual machines](images/container-vs-vm.webp)

---

## 🗺️ What's inside

| # | Chapter | What you'll learn |
|---|---------|-------------------|
| 0 | The big idea | What images and containers are |
| 1 | Set up Docker Desktop | Install it, check the engine is running, useful settings |
| 2 | Your first container | Run `hello-world` |
| 3 | Run a real web server | Find an image, open a port with `-p`, view it in your browser |
| 4 | Look inside a container | Logs, Inspect, Exec, Files, Stats |
| 5 | Keep your data with volumes | Delete the container, keep the data |
| 6 | Docker Compose | One file, one command, a whole stack |
| 7 | Stop, start and clean up | Stop, remove, free up disk space |
| 8 | Useful features & tips | Docker Scout, Extensions, the menu-bar whale |
| ★ | Cheat sheet | Buttons ↔ commands |

---

## 🖼️ Sneak peek

**Run a web server on your own Mac**, and watch it run in Docker Desktop:

![The my-web container running](images/my-web-running.webp)

Open your browser and there it is:

![Safari showing localhost:8080](images/localhost-8080.webp)

**Ports**: containers are sealed off by default. `-p` opens a door.

![What -p 8080:80 means](images/ports.webp)

**Volumes**: without a volume, data dies with the container. With one, a new container sees the same files.

![Volumes keep your data](images/volumes.webp)

**Docker Compose**: one file, one command, the whole stack starts together.

![Docker Compose](images/compose.webp)

---

## 🎬 Prefer video?

[`docker_desktop_guide.mp4`](docker_desktop_guide.mp4) is the video version of the whole guide. You can also play it at the top of the [online guide](https://tinggeorge.github.io/docker-beginner-guide/).

---

## 📁 Files

| File | What it is |
|------|------------|
| `index.html` | The guide itself (a single file with all images embedded; opens in any browser) |
| `docker_desktop_guide.mp4` | Video version of the guide |
| `images/` | Illustrations used in the READMEs |

## 💻 Read offline

```bash
git clone https://github.com/TingGeorge/docker-beginner-guide.git
open docker-beginner-guide/index.html
```
