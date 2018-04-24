# 重新选择AOD

## Prospects

1. G&H 4100 UV 

   之前就是在这家定制的

   * 声速 6170 m/s
   * 中心波长 364nm
   * RF Band: 75~125 MHz
     * 计算出 $\Delta \theta = \frac{\lambda \Delta f}{v_a} = 2.88$mrad, 波长取355
     * 工作距离 13mm ：偏转范围 37 micros
   * 入射光斑直径 ? 3mm
     * 发散角 $\Delta\phi = \frac{4\lambda}{\pi d}=0.15$mrad
     * 分辨点数 19

2. Isomet 1206C-2-1002

   * 声速 4200 m/s
   * 波长范围 360-420 & 442-488 ? 没cover 355？
   *  RF Band：110$\pm$25 MHz
     * 计算出 $\Delta \theta = \frac{\lambda \Delta f}{v_a} = 4.23$mrad, 波长取355
     * 工作距离 13mm ：偏转范围 55 micros
   * 入射光斑直径 ? 3mm
     - 发散角 $\Delta\phi = \frac{4\lambda}{\pi d}=0.15$mrad
     - 分辨点数 28



## 核心问题

tradeoff between  $N = \frac{\pi w_0\Delta f}{4v_a}$ & switching time $\tau = \frac{w_0}{v_a}$

* Estimate with N=60, $\tau=1\mu$s, $\Delta f=76$MHz.
* 所以如果RF带宽要到80MHz才有可能单个AOD够用



## 可尝试方案

1. 找到RF带宽足够宽的
2. AOD后靠其它开关加快切换
3. 段老师：级联。通过傅里叶面回避前级偏转对后级的影响