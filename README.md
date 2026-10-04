# 🍓 Raspberry Pi 5 (8 GB) Projects

This repository is a collection of projects and experiments built on the Raspberry Pi 5 with 8 GB of RAM. The goal is to explore what this small, low-cost, low-power computer can really do, from running artificial intelligence locally to working with hardware and software tools. Every project is documented step by step, so anyone can follow along and recreate it on their own Raspberry Pi.

## 🚀 Getting Started: Recommended Workflow

If this is your first time here, follow the steps below in order.

### Step 1: Complete the Memory Configuration Process
Start by setting up memory on your Raspberry Pi 5 (8 GB) so the AI models run smoothly.
📁 See [`Memory-Configuration-Process`](./Memory-Configuration-Process) (includes a video guide).

### Step 2: Share the Pi Using Command Prompt
Next, set up screen sharing from the command line.
📁 See [`Raspberry-Pi-Screen-Sharing-using-Command-Prompt`](./Raspberry-Pi-Screen-Sharing-using-Command-Prompt).

### Step 3: Connect with Raspberry Pi Connect
Go to [Raspberry Pi Connect](https://www.raspberrypi.com/software/connect/) to access your Pi from anywhere, using either:
- **Screen sharing** (full remote desktop), or
- **Remote shell** (terminal access)

### Step 4: Sign In Again When Needed
On later visits, if your session has expired, sign in again from the command prompt, then start screen sharing:

```bash
rpi-connect signin
```

Then open [connect.raspberrypi.com](https://connect.raspberrypi.com) in your browser and choose **Connect via screen sharing**.

## 🚀 About the Hardware

The Raspberry Pi 5 with 8 GB of RAM is one of the most capable single-board computers available for hobbyists and students. Its faster quad-core processor and larger memory make it suitable for tasks that were difficult on older models, such as running small language models, hosting web services, and handling multiple programs at once. All projects here are tested on Raspberry Pi OS (64-bit) with an active cooler and the official 27W power supply for stable performance.

## 🤖 Current Project: Local AI Chatbot

The first project is a private AI chatbot that runs entirely on the Raspberry Pi without internet access after setup. It uses a small open-source language model, so your conversations stay on your own device and there are no cloud services, API keys, or subscription fees. The folder includes a full process document explaining how to prepare the Pi, install the required software, download a model, and start chatting from the terminal or a web browser.

## 🔮 Upcoming Projects

More projects will be added over time as I keep learning and experimenting. Planned ideas include voice assistants, sensor and GPIO projects, home automation, and camera-based tools. Each new project will get its own folder with a README, a list of required parts, and clear setup instructions.

## 📁 Repository Structure

Each project lives in its own folder, which keeps the repository clean and easy to browse. Inside every folder you will find a README with an overview, requirements, installation steps, and troubleshooting tips, along with any supporting files such as documents, scripts, or images.

## 🤝 Contributing

Suggestions, bug reports, and improvements are always welcome. If you try one of these projects and run into a problem, or have an idea for a new one, feel free to open an issue or submit a pull request.

## 👤 Author

**SM Fahad** – [@SMFAHAD1](https://github.com/SMFAHAD1)
Email: smfahadfahad874@gmail.com

⭐ If you find this repository useful, please consider giving it a star!
