# Developer-Vs-Tester---Agentic-AI

## 🔄 Reflection Design Pattern in This Project

This project uses **Reflection** as an agent strategy — where the `Developer` agent reflects on feedback from the `Tester` agent, learns from it, and iteratively improves its code.

### 🧠 How It Works

1. The **Developer agent** generates initial code.
2. The **Tester agent** analyzes it, runs test cases, and gives feedback.
3. The **Developer** uses this feedback to **reflect and revise** the code.
4. This loop continues until the code passes or meets the criteria.

This emulates the **Reflection Design Pattern**: the system can inspect, evaluate, and modify its own behavior at runtime based on external feedback — a crucial concept in **LLM agent frameworks** like LangChain.

### 🔁 Benefits
- Dynamic learning without manual reprogramming
- Realistic developer-tester simulation
- Supports meta-cognitive behavior in AI agents
![image](https://github.com/user-attachments/assets/79c4e8a2-5432-45f5-b9d9-894e035b130b)

# Graph
![image](https://github.com/user-attachments/assets/860105f4-7b20-42fc-9501-5c6ba4429a69)

# 📜 Full Developer–Tester Conversation- for an example ("Write a python code for Tic-Toc-Toe Game")
![image](https://github.com/user-attachments/assets/ff923aeb-2f78-4526-b7d7-7cf752ef18c2)
![image](https://github.com/user-attachments/assets/bee64e99-f743-4984-bb23-8c4c3afd7724)
![image](https://github.com/user-attachments/assets/39d7bfe3-068b-4482-80c4-ad68cd161b5a)
![image](https://github.com/user-attachments/assets/ddeefa64-417b-4b16-89a4-2194d81464b6)
![image](https://github.com/user-attachments/assets/1dc10e6c-34b4-4f2e-896c-26b95433a241)
![image](https://github.com/user-attachments/assets/d669bcd6-5f9a-4d58-bfd9-10c3c5b62546)
![image](https://github.com/user-attachments/assets/a94b4e95-7781-48d9-afa9-8e46b3eb9c6e)
![image](https://github.com/user-attachments/assets/a53099a2-7f04-447d-99e3-1bcc9c103261)












## 🌐 Try It Now

This app is currently live at:

👉 **[Gradio Public Link](https://ade852361a353873ed.gradio.live)**  
(Note: This link will expire in 7 days)

Make sure to enter open Ai api key
---
## 🚀 Deploy This Notebook to Hugging Face Spaces

Follow these steps to deploy your Gradio notebook app permanently:

```bash
pip install gradio
huggingface-cli login
gradio deploy
