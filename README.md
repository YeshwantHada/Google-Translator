# **Google Translator – Python**

## **Overview**
This Python script provides an interactive command-line interface for translating text into multiple languages using the **googletrans** library. It supports asynchronous translation for better performance and responsiveness.

---

## **Features**
✔ Interactive language selection  
✔ Translate text into multiple languages  
✔ View pronunciation and source language  
✔ Asynchronous translation for efficiency  

---

## **Requirements**
Install dependencies:
```bash
pip install -r requirements.txt
```

`requirements.txt`:
```
googletrans==4.0.0-rc1
asyncio
```

---

## **Usage**
1. Run the script:
```bash
python src/Google_Translator.py
```
2. Enter a language code or type `options` to view available languages.
3. Enter text to translate.
4. Type `close` to exit.

---

## **Example Output**
```
Please input desired language code. To see the language code list, enter 'options':
options
Code : Language
en => English
fr => French
es => Spanish
...
You have selected French

Write the text you want to translate:
Hello World

French translation: Bonjour le monde
Pronunciation: Bonjour le monde
Translated from: English
```

---

## **License**
MIT License – Free to use and modify.

---

## **Author**
**Yeshwant Hada**  
https://github.com/YeshwantHada
