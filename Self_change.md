# Modifications
## Secondary fates:
### Todos
- [x] Functioning check
- [ ] ~~*存進去 但有時候似乎沒讀出來？*~~
- [x] Automaticlly change secondary_fate when fate changes
  - ~~comments in gui\config.py~~
  - [x] Show the modified secondary_fate 
  -   [ ] Secondary_fate GUI changes when editting
### Changes
- [.\utils\config.py]<br>
  Add type: secondary_fate
- [.\gui\config.py]<br>
  Add dropdowns: secondary_fate 1-3
## Speed up
- [x] [.\gui\Choose.py] 
  - after `go_about()`<br>
    `time.sleep(1)` <- 減少
----------------
# Want to change
- [x] 上傳Github
- [ ] 復活？(no ideas)
- [ ] cmd添加黃泉開關
- [ ] count 100:
  - 次數存在notif
- [ ] 設定內容記憶
- [ ] 手動給加拉赫開Q
- [ ] 一些事件的優先程度
- [ ] 打罐子
- [ ] 優先級理解或更改：
  - [ ] 副命途優先程度
  - [ ] 優先戰鬥->優先事件
    - 兩個藍門的時候他選什麼？
  - [ ] 祝福星數優先程度
    - 智能強化？
    - OpenCV

# Done locally
## Leave at eight floor
### Code
- [.\states.py] 500 
- [.\utils.py] 1284
+ *暫未試跑*

### GUI
- Add stwitch **只打八層**
- Add function of stwitch

## Huangquan E mode
### Code
- [.\states.py] 387
### GUI
- Add stwitch **黃泉專屬**
- Add function of stwitch

## Log level
### Code
- info log -> debug log
  - [utils.py 405]
