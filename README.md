# Encode_Source_Python

## Introduction

Bộ công cụ này giúp những nhà phát triển chia sẻ và công bố sản phẩm bản quyền để tránh ăn cắp nội dung của các tệp tin.

## METHOD

- Mã hóa dựa trên một khóa key tự do và khởi tạo bộ mã hóa dự trên khóa key đó
- Khởi tạo được bộ mã theo quy luật khóa và tách không gian và đường của bộ mã
- Mã hóa ASCII bộ mã
- Tạo biến mới và các giá trị số ngẫu nhiên
- Tạo các Var mới và xáo trộn nó một cách ngẫu nhiên dựa trên quy luật tái tạo key
- Thêm các Var đã được chuyển đổi
- Ghép tất cả và tạo bộ mã cuối cùng

- Quá trình được tái tạo 5 lớp chống unpack và decode file

## SETUP

## Setup

```
1. Clone the repository:
> git clone https://github.com/hoangmanhkhiem/Encode_Source_Python.git

2. Change into the project directory:
> cd automatically-evaluate-teachers

3. Create a virtual environment:
> py -m venv venv

4. Activate the virtual environment:
> source venv/bin/activate (Linux)
> venv\Scripts\activate (Windows)

```

## USAGE

```
python encode.py -i input_file.py -o output_file.py
```



