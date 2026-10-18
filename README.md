# beta_chassis_pcb

## 役割

車体側の受動分配基板。マイコンは載せず、電源を車輪 ESC 4 台に分配し、CAN を分配する。

## 主要部品

| 部品 | 型番 | 用途 |
|---|---|---|
| 電源入力コネクタ | AMASS XT30U-M × 1 | |
| ESC 電源コネクタ | AMASS XT30U-F × 4 | 車輪 ESC × 4 |
| CAN コネクタ | JST PH B2B-PH-K × 5 | 車輪 ESC × 4 + 砲塔側 |
| 6P コネクタ | JST PH B6B-PH-K × 1 | 砲塔側への出力 |

回路図は [beta_chassis.pdf](./beta_chassis.pdf)、部品表は [bom.csv](./bom.csv)、3D は [beta_chassis.step](./beta_chassis.step)。

## ライセンス

© Rabbits Robotics、[CERN-OHL-P-2.0](./LICENSE)。
