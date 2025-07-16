# 🧪 Ayineun's Chatbot (Trial Build)

> A basic intent-based chatbot built with Python, TensorFlow, and Keras.

This was a learning experiment — building an end-to-end chatbot with custom intents, NLP preprocessing, and a simple neural network.

---

## ⚙️ Features

- Tokenizes and lemmatizes input using NLTK
- Vectorizes text using bag-of-words
- Trains a simple feedforward model with Keras
- Returns responses based on predicted intent

---

## 📁 Project Structure

ayineun-chatbot/
├── test.json  
├── train_chatbot.py  
├── chat.py  
├── words.pkl  
├── classes.pkl  
├── test_bot.h5  
├── requirements.txt  
└── README.md


## ⚠️ Do I Need to Retrain the Bot?

If you're just here to try the bot — **nope!** The trained model (`test_bot.h5`) and supporting files (`words.pkl`, `classes.pkl`) are already included.

But if you:
- Modify the `test.json` intent file
- Add new tags or responses

...then you'll need to retrain the model:

python train_chatbot.py

Then feel free to chat:

python chat.py


---

### ✌️ Final Note

Thanks for checking out this lil’ chatbot experiment. It might be dumb now, but every line of code is a step toward building something brilliant.

Go ahead — fork it, tweak it, break it, vibe with it.

Peace out ✌️  
**— Ayineun**

---

## 🛡️ License

MIT — remix it, break it, teach it some new tricks. Just don’t bully it too hard.
