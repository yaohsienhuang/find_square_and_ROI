# find_square_and_ROI
- 影像處理方式找出圖片中的方形所有可能方形物件
- 條件篩選 (width,heigh,area,etc...) 可能出可能的鋁墊PAD位置
- 使用 cv2.approxPolyDP 多邊形逼近，辨別針痕是否碰邊

![截圖 2022-10-04 下午5 05 43](https://user-images.githubusercontent.com/107407057/193780416-9e94c3c6-79d6-4128-a4e4-a072b1129781.png)

