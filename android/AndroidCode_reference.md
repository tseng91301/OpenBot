# Android 原始碼解析
## Openbot.robot
### 重要文件路徑
1. org.openbot.common.FeatureList: 定義app內功能選項的程式碼(Class)，可以在裡面增加功能選項，並附上圖片和title文字
2. org.openbot.main.MainFragment: 用來載入App 的主畫面並定義功能觸碰的功能
3. org.openbot.tflite.Detector: 定義對影像執行物件偵測的相關程式
4. org.openbot.tracking.MultiBoxTracker: 用來定義辨識物體方形框的性質(顏色、字體等)
6. org.openbot.tflite.DetectorDefault, DetectorYoloV4, DetectorYoloV5: 各個偵測模型的判斷程式，透過Detector中的 abstract function 呼叫