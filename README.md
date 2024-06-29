# 🔓 FristiLeaks Password Decoder 🔓

Welcome to the FristiLeaks Password Decoder! This Python script is designed to decode encoded passwords found on the FristiLeaks machine from VulnHub. The script takes an encoded string as input and reveals the original password through a series of decoding steps. 

To download fristileaks, click [here](https://www.vulnhub.com/entry/fristileaks-13,133/)
## 🔍 How It Works

The FristiLeaks Password Decoder follows these steps to decode the password:
1. 🔄 **ROT13 Decoding:** The script first decodes the input string using the ROT13 cipher, which shifts each letter 13 places in the alphabet.
2. 🔁 **Reversal:** The decoded string is then reversed.
3. 🗝️ **Base64 Decoding:** Finally, the reversed string is decoded using Base64 to reveal the original password.

## 🚀 Usage

1. **📥 Install Python:**
   Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/).

2. **💾 Download the Script:**

   ```shell
   git clone 'https://github.com/RIZZZIOM/fristidecoder.git'
   cd fristidecoder
   ```

3. **🖥️ Run the Script:**
   
   ```bash
   python fristidecoder.py
   ```

4. **⌨️ Enter the Encoded String:**
   When prompted, enter the encoded string that you want to decode.

5. **🔐 View the Decoded Password:**
   The script will print the decoded password.

## 📝 Example

Here's a step-by-step example of using the script:

1. **▶️ Run the Script:**

   ```bash
   python fristidecoder.py
   ```
   
2. **🆔 Input the Encoded String:**

   ```plaintext
   Enter the string: cnrFGVQhZGVrMw==
   ```
   
3. **📜 Output:**

   ```plaintext
   The string is: password123
   ```

---

Enjoy using the FristiLeaks Password Decoder! If you have any questions or suggestions, feel free to reach out. 😊