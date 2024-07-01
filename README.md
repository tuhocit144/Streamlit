# Streamlit
Project about using Streamlit to build applications of Machine Learning

## Giới Thiệu
Project này với mục đích giúp làm quen với cách sử dụng Streamlit để xây dựng 1 ứng dụng web cho các dự án Machine Learning
Project này bao gồm các bài toán cơ bản:
+ Sửa lỗi chính tả
+ Dectect object
+ Chatbot

## Hướng Dẫn Cài Đặt

1. Cài đặt thư viện:
    ```bash
    pip install streamlit
    ```
2. Kiểm tra cài đặt streamlit:
    ```bash
    streamlit hello
    ```
3. Sử dụng streamlit trong project:
   ```bash
    import streamlit as st
    ```
## Xây dựng các thành phần trên giao diện
1. Đặt tiêu đề cho ứng dụng của bạn bằng cách sử dụng st.title(), ví dụ:
   ```bash
    st.title('My project in Streamlit')
   ```
2. Tạo header cho ứng dụng bằng cách sử dụng st.header(), ví dụ:
   ```bash
    st.header('This is header')
   ```
3. Tạo subheader cho ứng dụng bằng cách sử dụng st.header(), ví dụ:
   ```bash
    st.subheader('This is a sub header')
   ```
4. Tạo subheader cho ứng dụng bằng cách sử dụng st.header(), ví dụ:
   ```bash
    st.subheader('This is a sub header')
   ```
5. Hiển thị chuỗi được định dạng là Markdown bằng cách sử dụng st.markdown(), ví dụ:
   ```bash
    st.markdown('My lesson for beginner')
   ```
6. Hiển thị các biểu thức toán học được định dạng là LaTeX, sử dụng st.latex(), ví dụ:
    ```bash
     st.latex('\sqrt{2x}')
    ```
7. Hiển thị dữ liệu là biến hoặc text bằng cách sử dụng st.write(), ví dụ:
   ```bash
    st.write('Hello An')
   ```
8. Hiển thị hình ảnh bằng cách sử dụng st.image(), ví dụ:
   ```bash
    st.image('dogs.PNG','Funny picture')
   ```
9. Hiển thị audio bằng cách sử dụng st.audio(), ví dụ:
   ```bash
    st.audio('henuoctuhuvo.mp4','My favorite song')
   ```
10. Hiển thị video bằng cách sử dụng st.video(), ví dụ:
    ```bash
    st.video('kh01.mp4')
    ```
11. Hiển thị checkbox cho phép người dùng chọn hay không chọn bằng cách sử dụng st.checkbox(), ví dụ:
    ```bash
    agree=st.checkbox("I agree!")
    ```
12. Hiển thị radio button bằng cách sử dụng st.radio(), ví dụ hiển thị 2 radio button là Yellow và Blue:
    ```bash
    status=st.radio('Your Favorite color: ',['Yellow','Blue'])
    ```
13. Hiển thị combobox cho phép chọn nhiều lựa chọn bằng cách sử dụng st.multiselect(), ví dụ:
    ```bash
    st.multiselect('Colors:',['Green','Yellow','Blue'], 
     ['Yellow','Blue'])
    ```
14. Hiển thị thanh trượt (slider) bằng cách sử dụng st.select_slider(), ví dụ:
    ```bash
    st.select_slider('Your color:',['Red','Yellow','Blue'])
    ```
15. Sử dụng button để thực hiện một hành động nào đó bằng cách sử dụng st.button(), ví dụ:
    ```bash
    if st.button('Submit'):
       st.write("Hello An")
    else:
       st.write("Goodbye")
    ```
16. Nhập dữ liệu thông qua một textbox bằng cách sử dụng st.text_input(), ví dụ:
    ```bash
    st.text_input('Your name: ',value='Annna')
    ```
17. Upload file bằng cách sử dụng st.file_uploader(), thiết lập accept_multiple_files=True cho phép upload nhiều file cùng lúc, ví dụ:
    ```bash
    st.file_uploader('Nhập file cần upload:',accept_multiple_files=True)
    ```
18. Hiển thị đường kẻ ngang trang bằng cách sử dụng st.divider(), ví dụ:
    ```bash
    st.divider()
    ```
## Project sử dụng Streamlit xây dựng các ứng dụng: 

+ Word Correction
+ Object Detection
+ Chatbot

1. Clone repository:
    ```bash
    git clone https://github.com/tuhocit144/Streamlit.git
    ```
2. Chuyển đến thư mục dự án:

    ```sh
    cd Streamlit
    ```
3. Chạy các ứng dụng trong project
   #### Sửa lỗi văn bản
   ```sh
    Streamlit run levenshtein_distance.py
   ```
   #### Object detect 
   ```sh
    Streamlit run object_detect.py
   ```
    #### Chatbot 
    ```sh
    Streamlit run chatbot.py
   ```
