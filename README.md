# 107AB0739-final

## 程式功能

使用RandomForestClassifier 及 FeatureHasher抓出檔案特徵，做機器學習來找出惡意程式特徵，分辨為善意或惡意程式，畫出ROC curves圖。

## 運作方式

get_string_features：找出檔案特徵並且存放於陣列。
scan_file：掃描檔案判斷為善意或惡意
train_detector：以RandomForest訓練detetor。
cv_evaluate：以scores和test_y分辨為善意或惡意檔案畫出ROC curves圖。

## 執行結果


![] (https://github.com/Linwc720/107AB0739-final/blob/main/%E6%93%B7%E5%8F%96.PNG)


## 心得

這門課教的東西對我來說真的是蠻困難的，常常聽到一半就突然迷失，好在同學很給力，總能跟我解釋老師所講的東西，讓我還是能理解老師所教的，真的很感謝他，也謝謝老師為我們準備的上課內容，真的是受益良多。
