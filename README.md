# **SACRO - Sound Macro**
![Alt text](https://i.imgur.com/TT7PFG5.jpeg)
This project was inspired to me by my little brother who plays the infamous game on **Roblox, Steal a Brainrot**. Basically, the purpose of this project is to input the keypress "**E**" whenever the microphone detects the phrase of a special brainrot. 

Later on, I'll most likely adjust the code to also fit my needs such as quickly opening up my favourite game, opening YouTube, etc. For now, the AI module is trained to recognize three phrases from Steal a Brainrot, with the code written to press E whenever one of them is detected.

![Alt text](https://uk.moyens.net/wp-content/uploads/2025/07/Unlocking-Secret-Brainrots-Master-Steal-a-Brainrot-Game-Tips.webp.jpeg)

---

### **Bill of Materials (BOM)**

| Item Name | Quantity | Base Price (CAD) | Discounted Price (CAD) | Link | Description |
|-----------|---------|-----------------|------------------------|---------------|-------------|
| ESP32 S3 Supermini | 1 | 15.49 | 1.64 | [Aliexpress](https://www.aliexpress.com/item/1005009437349894.html) | Microcontroller for project |
| I2S Microphone INMP441 | 1 | 2.89 | 1.64 | [Aliexpress](https://www.aliexpress.com/item/1005006740892303.html) | Microphone to detect phrases |
| Flexible Copper Wire Bundle | 1 | 3.15 | 1.64 | [Aliexpress](https://www.aliexpress.com/item/1005006467312913.html) | Wires to connect the two module's pins together |
---
### **Recreational Purposes**
To use this build for your own purposes you can use the wiring diagram I made; however, you'll certainly want to be changing the code, unless you're using this for Steal a Brainrot as well. Additionally, you will also have to train your own AI Model and import it with your code. Personally, I find using Edge Impulse a good tool to train your AI Model as I was able to make it familiarize with 3 phrases in under 15 minutes with the help of the tutorial.

---
### **Note**: Keep in mind how much space (KB) your code requires, since the ESP32 S3 Supermini doesn’t have a large amount of storage.
