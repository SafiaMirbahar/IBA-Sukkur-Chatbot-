# IBA-Sukkur-Chatbot-

A smart chatbot built using Python and Tkinter for answering common questions about IBA Sukkur. It first searches through local FAQ data using TF-IDF and cosine similarity (via scikit-learn). If the question doesn’t match any stored answer confidently, it automatically queries the Gemini API to provide a more accurate and updated response — including information from the official IBA Sukkur website.

