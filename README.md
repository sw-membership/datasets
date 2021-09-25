# datasets

주식 긍부정 분석을 위한 데이터셋입니다.

## 전처리

영어의 경우 알파벳, 숫자 그리고 일부 기호('",.-)를 제외한 나머지를 보무 삭제해야 합니다.

## labels

레이블은 다음으로 처리되었습니다.

- -1: 부정
- 0: 중립
- 1: 긍정

## example

```shell
# data.csv
index,text,labels
1,hello world,-1
2,hi there,0
```

## [data](data/)

### [SAFFN](data/saffn.csv)

[Sentiment Analysis for Financial News](https://www.kaggle.com/ankurzing/sentiment-analysis-for-financial-news/)
