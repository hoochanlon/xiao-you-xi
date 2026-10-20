## DualSense 按键对照表（InputConfig）

> [!important]
> * [疯兔游戏](https://www.fengtu.org/)游戏机模拟器FBNeo完整包：https://www.fengtu.org/finalburn-neo.html
> * RetroArch（多平台的模拟器）：https://www.retroarch.com/?page=platforms

AntiMicroX 为 Windows/Linux 是手柄-键盘的映射辅助工具：https://github.com/AntiMicroX/antimicrox 

在 Mac上有 InputConfig:：https://inputconfig.com

FC、街机金手指大全：https://cheats.lxyong.com 、https://gamehacking.org

### 十字键（D-pad）

| 方向        | Input 类型 | 说明              |
| ----------- | ---------- | ----------------- |
| 上/下/左/右 | **Hat**    | 不是 Axis，是 Hat |


### 摇杆（Axis）

| 位置       | 动作 | Input 设置 | 方向  | 建议映射键盘 |
| ---------- | ---- | ---------- | ----- | ------------ |
| **左摇杆** | 向左 | Axis #0    | **-** | Left 或 A    |
| **左摇杆** | 向右 | Axis #0    | **+** | Right 或 D   |
| **左摇杆** | 向上 | Axis #1    | **-** | Up 或 W      |
| **左摇杆** | 向下 | Axis #1    | **+** | Down 或 S    |
| **右摇杆** | 向左 | Axis #2    | **-** | 自定义       |
| **右摇杆** | 向右 | Axis #2    | **+** | 自定义       |
| **右摇杆** | 向上 | Axis #3    | **-** | 自定义       |
| **右摇杆** | 向下 | Axis #3    | **+** | 自定义       |

### 正面四键（Button）

| 按键名称     | 常见叫法   | Input 显示名称    | 建议映射 |
| ------------ | ---------- | ----------------- | -------- |
| **Cross**    | × / X      | Button (Cross)    | 自定义   |
| **Circle**   | ○ / 圆形   | Button (Circle)   | 自定义   |
| **Square**   | □ / 正方形 | Button (Square)   | 自定义   |
| **Triangle** | △ / 三角   | Button (Triangle) | 自定义   |

### 肩键 & 摇杆按下（Button）

| 按键   | Input 显示名称         | 说明                 |
| ------ | ---------------------- | -------------------- |
| **L1** | LB / L1                | 左肩键               |
| **R1** | RB / R1                | 右肩键               |
| **L2** | LT / L2（有时是 Axis） | 左扳机（可模拟按键） |
| **R2** | RT / R2（有时是 Axis） | 右扳机（可模拟按键） |
| **L3** | L3 (left stick click)  | 左摇杆按下           |
| **R3** | R3 (right stick click) | 右摇杆按下           |

### 其他按键（Button）

| 按键         | Input 显示名称 | 说明       |
| ------------ | -------------- | ---------- |
| **Create**   | Create / Share | 原分享键   |
| **Options**  | Options        | 选项键     |
| **PS**       | PS Button      | PS 键      |
| **Mute**     | Mute           | 静音键     |
| **Touchpad** | Touchpad       | 触摸板点击 |

### 连发设置步骤

1. 找到你想设置连发的那一行（比如某个 Button 映射成空格或攻击键）。
2. 点击该行下方的 **Options**（展开选项）。
3. 找到 **How it fires**（触发方式），选择以下两种之一：

| 模式                            | 中文意思   | 效果                                         |
| ------------------------------- | ---------- | -------------------------------------------- |
| **Repeats while held**          | 按住时重复 | 按住按钮就一直连发，松手停止（最常用连发）   |
| **Repeats until pressed again** | 按一下开关 | 按一下开始连发，再按一下停止（自动连发开关） |

1. 设置 **Every**（间隔时间，单位毫秒）：
   - **50 ms** ≈ 每秒 20 次（较快连发）
   - **80–100 ms** ≈ 每秒 10–12 次（比较自然）
   - **30 ms** 左右可以更快（但部分游戏可能不识别）
2. 可选设置：
   - **Vary by up to**：给间隔加一点随机，看起来更自然
   - **Stop after**：连发固定次数后自动停止
3. 点 **保存**，然后 **Activate** 启用预设测试。

