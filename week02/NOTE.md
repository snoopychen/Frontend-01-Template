### 按语法分类

#### 非形式语言

    - 中文，英文

#### 形式语言（乔姆斯基谱系）

    - 0型 无限制语法
    - 1型 上下文相关文法
    - 2型 上下文无关文法
    - 3型 正则文法

### 产生式（BNF）

    A :: B 
    介绍BNF => 用于JS 规范的阅读，更易入手

### 动态和静态

    #### 动态
        - 在用户的设备/在线服务器上
        - 产品实际运行时
        - runtime

    #### 静态
        - 在程序员的设备上
        - 产品开发时
        - Compiletime

### 类型系统

    - 动态类型系统与静态系统类型
    - 强类型和弱类型

### 基本类型

    - Null
    - Undefined
    - Boolean
    - String
      - 支持码点: U+0000 ~ U+10FFFF， 但推荐只使用 U+0000 ~ U+FFFF （BMP）
      - 编码方式：UTF-8/UTF-16
    - Number IEEE754
      - 0.1 + 0.2 === 0.3 // false
      - Math.abs(0.1 + 0.2 - 0.3) < Number.EPSILON // true
      - 但是：Math.abs(1.1 + 1.2 - 1.3) < Number.EPSILON // false
