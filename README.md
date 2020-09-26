# Học không giám giát để trích xuất khía cạnh
Dựa theo code từ project sau: https://github.com/ruidan/Unsupervised-Aspect-Extraction
Và https://github.com/swordmanager/sentiment_analysis_nal
## Dữ liệu
Dữ liệu là comment lấy từ trang foody.vn
Vào thư muc data_clean chạy file clean_data.ipynb
## Công cụ và thư viện
IDE: jupyter notebook.
Python 3:
- Keras 2.4.3
- Tensorflow 2.3.0
- numpy 1.17.2
- pandas 0.25.1
- gensim 3.8.3
- import-ipynb 0.1.3
- underthesea 1.1.17
- scikit-learn 0.20.3
- tqdm
## Training
Vào thư mục code chạy file train.ipynb

## Cite
```
@InProceedings{he-EtAl:2017:Long2,
  author    = {He, Ruidan  and  Lee, Wee Sun  and  Ng, Hwee Tou  and  Dahlmeier, Daniel},
  title     = {An Unsupervised Neural Attention Model for Aspect Extraction},
  booktitle = {Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  month     = {July},
  year      = {2017},
  address   = {Vancouver, Canada},
  publisher = {Association for Computational Linguistics}
}
```