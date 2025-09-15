# -Project-of-Microprocessor-Laboratory
本專題以 HT32F49395 開發板 與 Edge Impulse 平台為基礎，結合 MPU6050 三軸感測器，實作姿勢辨識系統。系統透過 I2C 介面擷取加速度資料，並利用 Edge Impulse 建立與訓練機器學習模型，辨識 forward、backward、leftward、rightward 等不同手勢。完成訓練後，模型以 CMSIS-Pack 格式部署至 HT32F49395，並在 Keil 環境中撰寫推論程式，使使用者能以手勢即時控制車輛移動。此專題展現了嵌入式系統、感測器應用與 AI 模型部署的整合能力。而我在團隊中主要是負責報告書撰寫及實驗的協助。

demo 影片連結: https://youtu.be/DIOmPT7g-0Q
<figure>
  <img width="280" height="559" alt="Image" src="https://github.com/user-attachments/assets/1e15e2f3-78f1-44ae-b4d2-21414387e805" />
  <figcaption>圖1.系統架構圖</figcaption>
</figure>
