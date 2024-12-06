# 🤖 ChatBot-With-LangChain
## 👽 Retrieval Augmented Generation (RAG) architecture by Aurimas Griciūnas
![alt text](<pipline rag.gif>)
## 📃YÊU CẦU HỆ THỐNG 
- Python 3.8 trở lên, khuyến nghị version 3.8.18 (Tải tại: https://www.python.org/downloads/)
- Docker Desktop (Tải tại: https://www.docker.com/products/docker-desktop/)
- OpenAI API key (Đăng ký tại: https://platform.openai.com/api-keys)
- Khoảng 4GB RAM trống
## 🚀 CÁC BƯỚC CHẠY VÀ CÀI ĐẶT
**CÁCH 1 : Tải và xử lý dữ liệu**
1. DSFDSAFD
2. FDSFDSA
3. DSFDSA

__CÁCH 2 : Tải và xử lý dữ liệu__
* DSFDSAFD
* FDSFDSA
* DSFDSA

___BƯỚC 3 : CÀI ĐẶT VÀ CHẠY MILVUS DATABASE___
1. đối với window , cài đặt và mở docker desktop lên 
2. mở termial di chuyển đến thư mục gốc của source và chạy lệnh 
```
docker-compose up -d
```
3. optional : attu để có giao diện data đã seed vào Milvus:
    
    3.1. mở termianl gõ lệnh : `ifconfig eth0`
    
    3.2. chạy lệnh docker run -p 8000:3000 -e MILVUS_URL={milvus server IP}:19530 zilliz/attu:v2.4
    
    3.3. thay {milvus server IP} thành ip mà lệnh ifconfig etho0 đã trả ra 
    
*CÁCH 4 : Tải và xử lý dữ liệu*
- DSFDSAFD
- FDSFDSA
- DSFDSA

***CÁCH 5 : Tải và xử lý dữ liệu***
- retrieval này đã được sử dụng [github pages](https://pages.github.com/)
- đây là trang web mà tôi tự xây dựng bằng html , css , js ,thuần ở năm 2 [web by huy](https://huynopro102.github.io/34_app_music/)
- DSFDSA

## 💻 CÁCH SỬ DỤNG

***1. khỏi động dự án***
1. Chạy lệnh: `streamlit run main.py`
2. seed data vào Milvus : 
```
python crawl.py
```
## CÁC TÀI LIỆU THAM KHẢO ##

***1. NGƯỜI HƯỠNG DẪN***
- https://www.youtube.com/@DuTrendGenerativeAI

***2. SOURCE CODE CHÍNH***
- https://github.com/kaizenX209/Build-An-LLM-RAG-Chatbot-With-LangChain-Python

***3. KIẾN TRÚC RAG***
- https://www.linkedin.com/in/aurimas-griciunas/

***3. LANGCHAIN***
- langchain : https://smith.langchain.com/ 
- agents : https://python.langchain.com/docs/tutorials/qa_chat_history/#tying-it-together-1
- bm25 : https://python.langchain.com/docs/integrations/retrievers/bm25/#create-a-new-retriever-with-documents
- How to combine results from multiple retrievers: https://python.langchain.com/docs/how_to/ensemble_retriever/