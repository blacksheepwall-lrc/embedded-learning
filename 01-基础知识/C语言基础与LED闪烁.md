01-基础知识/C语言基础与LED闪烁.md
# C语言基础与板载LED闪烁

**日期**：2026年10月12日

## 今天学到的内容

### 1. 变量与数据类型
- `int`：整数类型
- 示例：`int delay_time = 500;`

### 2. if 判断
- 基本语法：
```c
if (条件) {
    // 执行的代码
}
for (int i = 0; i < 次数; i++) {
    // 循环执行的代码
}
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
