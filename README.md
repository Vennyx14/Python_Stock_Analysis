# Visa (V) Stock Volatility Analysis

## Mô tả
Phân tích biến động giá cổ phiếu V (Visa) trong 1 năm.

## Cấu trúc project
├── Stock_Analysis.ipynb # Notebook chứa toàn bộ code và giải thích
├── data/
│ ├── visa_raw.csv # Dữ liệu gốc
│ └── visa_clean.csv # Dữ liệu đã làm sạch
├── report.pdf # Báo cáo xuất từ Notebook
├── requirements.txt # Danh sách thư viện
└── README.md # File hướng dẫn này


## Cài đặt environment

python -m venv .venv
.\.venv\Scripts\Activate.ps1  # PowerShell
pip install -r requirements.txt

## Mở Stock_Analysis.ipynb và chạy toàn bộ cell
jupyter lab

## Tài liệu tham khảo

- Hướng dẫn
    - Python yfinance documentation
    - Pandas user guide
    - TA-lib & ta library docs
    - “Technical Analysis of Financial Markets” – John J. Murphy
    - Seaborn & Matplotlib documentation
- Link các web tham khảo
    - https://blog.quantinsti.com/tag/python-for-trading/
    - https://blog.quantinsti.com/tag/python-for-trading/
    - https://www.investopedia.com/