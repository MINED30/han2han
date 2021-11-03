작성중
- pipeline code
- finetuning & inference code
- embedding module
- model schematic diagram
- explanation
- demo
- colab tutorial
- packaging

<a href="https://colab.research.google.com/github/MINED30/HAN2HAN/blob/main/colab_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# HAN2HAN
Korean Handwriting Style Font Generation


```
git clone https://github.com/MINED30/HAN2HAN
cd HAN2HAN
mkdir targetimg
bash download.sh
python generate.py
```

### additional
```bash
python utils/Font2Numpy/font2numpy.py # TTF file to numpy array
```

## 결과물 (임시)

### Input
![image](https://user-images.githubusercontent.com/73981982/138725507-fa104664-bbed-47a5-b125-614a5348f70c.png)


### 10글자('나랏말싸미 듕귁에달아')로 만들어낸 윤동주 시인의 서시


![image](https://user-images.githubusercontent.com/73981982/138566749-9933493e-b29a-45a6-999e-314b33f3f3b8.png)
