# streamlit_app.py
import streamlit as st  

st.title('Hello, Streamlit!')  

st.write('This is a simple Streamlit app.')  

user_input = st.text_input("Enter something:")  
st.write(f'You entered: {user_input}')  
