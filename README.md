  # Wall Damage Detection Project
├── dataset_wall/                    # 訓練與測試資料集                                                                                                                
│   ├── wall_damage/                 # 用於 CNN 訓練的資料集                                                                                                          
│   │   ├── A/                       # Class A 的圖片資料夾                                                                                                            
│   │   ├── B/                       # Class B 的圖片資料夾                                                                                                          
│   │   ├── C/                       # Class C 的圖片資料夾                                                                                                            
│   └── wall_crack/                  # 用於 YOLOv8 訓練的資料集                                                                                                        
│       ├── train/                   # 訓練集                                                                                                                          
│       │   ├── images/              # 訓練圖片                                                                                                                        
│       │   ├── labels/              # 訓練標註檔                                                                                                                      
│       └── test/                    # 測試集                                                                                                                          
├── wall_crack.yaml                  # YOLOv8 訓練資料設定檔                                                                                                          
├── best_multitask_model.pth         # EfficientNetV2-S 模型檔案                                                                                                      
├── runs/                            # YOLOv8 訓練輸出                                                                                                                
├── wall_submission.csv              # 推論結果輸出檔案                                                                                                                
├── README.md                        # 專案說明文件                                                                                                                    
├── environment.yml                  # Conda 環境設定檔                                                                                                                
└── DLCV_Final_Competetion_Wall_CNN_YoloV8.ipynb # 主程式碼 (包含訓練與推論)                                                                                            
  Competetion2_Datasets_Link                                                                                                                                                                                          
  https://drive.google.com/drive/folders/1yDLcu1347yMhLSPXw9Mpt0ZT-po1hdvV?usp=sharing
