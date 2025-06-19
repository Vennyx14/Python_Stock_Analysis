# Visa (V) Stock Volatility Analysis

## Mô tả
- Phân tích biến động giá cổ phiếu V (Visa) trong 2 năm.
- Sử dụng các phương pháp như: IQR / Z-Score để xử lí outliers
- Chỉ số kĩ thuật sử dụng: SMA, EMA, RSI, MACD
- Đồ thị biểu diễn giá cổ phiếu cùng với các chỉ báo để phân tích
- Diễn giải, phân tích và đưa ra kiến nghị

## Cấu trúc project
    ├── Stock_Analysis.ipynb # Notebook chứa toàn bộ code
    ├── data/
    │ ├── visa_raw.csv 
    │ └── visa_clean.csv 
    ├── requirements.txt 
    └── README.md 


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
    - https://blog.bytescrum.com/python-for-finance-analyzing-stock-data-with-pandas#heading-combining-indicators-for-better-insights
