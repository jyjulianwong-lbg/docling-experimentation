# Docling Experimentation

## Conversion Speed

| File Name                          | Pages | Environment | Runtime | OCR |
|------------------------------------|-------|-------------|---------|-----|
| Vodafone 2025 Annual Report 10.pdf | 10    | Windows 365 | 122     | Off |
| Vodafone 2025 Annual Report 10.pdf | 10    | Windows 365 | 130     | RapidOCR |
| Vodafone 2025 Annual Report 10.pdf | 10    | Windows 365 | 697     | EasyOCR (Full-page OCR) |

## Conversion Quality

### With full-page OCR enabled
- More footnotes and small print were picked up.
- Tabular data remained the same.
- Unable to pick up images. These will be filled with the `<!-- image -->` placeholder.

## Required External Downloads

### EasyOCR
- (TBC)

### RapidOCR
- https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.4.0/torch/PP-OCRv4/det/ch_PP-OCRv4_det_infer.pth
    - C:\dev\projects\docling-experimentation\.venv\Lib\site-packages\rapidocr\models\ch_PP-OCRv4_det_infer.pth
- https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.4.0/torch/PP-OCRv4/cls/ch_ptocr_mobile_v2.0_cls_infer.pth
    - C:\dev\projects\docling-experimentation\.venv\Lib\site-packages\rapidocr\models\ch_ptocr_mobile_v2.0_cls_infer.pth
- https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.4.0/torch/PP-OCRv4/rec/ch_PP-OCRv4_rec_infer.pth
    - C:\dev\projects\docling-experimentation\.venv\Lib\site-packages\rapidocr\models\ch_PP-OCRv4_rec_infer.pth
- https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.4.0/resources/fonts/FZYTK.TTF
    - C:\dev\projects\docling-experimentation\.venv\Lib\site-packages\rapidocr\models\FZYTK.TTF