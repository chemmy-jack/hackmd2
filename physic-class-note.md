<style>
.markdown-body, .reveal{font-family: 'Times New Roman', 'biaukai';}
</style>
# 高老師物理課筆記
###### tags: `physics` `note`
[github data repo](https://github.com/chemmy-jack/hackmd2)
## 熱力學定律
* $Q=W+\Delta E=p\Delta \bar V=\int Pd\bar V+\frac{3}{2}\Delta (PV)=\int Pd\bar V+\frac{3}{2}nR\Delta T$
* ==$dQ=dW+dE$==
* $\gamma=\frac{C_p}{C_{\bar V}}R$
### 單原子理想氣體 
* ==$\gamma=\frac{5}{3}$==
* 定壓: 
    * $Q=P\Delta V + \frac{3}{2}nr\Delta T=nR\Delta T + \frac{3}{2}nr\Delta T=n(\frac{5}{2}R)\Delta T=nC_P\Delta T$
    * $C_T=\frac{5}{2}R$
* 定容: 
    * $Q=\int P\Delta \bar V+\Delta E=0+\frac{3}{2}nR\Delta T=n(\frac{3}{2}R)\Delta T=nC_{\bar V}\Delta T$
    * $C_{\bar V}=\frac{3}{2}R$
### 雙原子理想氣體
* ==$\gamma=\frac{7}{5}$==
* 定壓: $C_{\bar V}=\frac{5}{2}R$
* 定容: $C_P=C_{\bar V}+R=\frac{7}{2}R$
### 多原子理想氣體
* ==$\gamma=\frac{4}{3}$==
* 定壓: $C_{\bar V}=\frac{6}{2}R$
* 定容: $C_P=C_{\bar V}+R=\frac{8}{2}R$
### 絕熱情況 
==$P\bar V^\gamma =constant$==
$Q=0=\int Pd\bar V+\Delta E$
$\Rightarrow dQ=0=Pd\bar V+nC_{\bar V}\Delta T=pd\bar V+\frac{C_{\bar V}}{R}(dP\bar V+Pd\bar V)$
$\Rightarrow 0=RPd\bar V+C_{\bar V}dP\bar V+C_{\bar V}d\bar VP$
$\Rightarrow (C_{\bar V}+R)Pd\bar V=C_PPd\bar V+C_\bar V dP\bar V=0$
$\Rightarrow C_P\int \frac{d\bar V}{\bar V}+C_\bar V\int \frac{dP}{P}=0$
$\Rightarrow C_Pln\bar V+C_\bar VlnP=ln(P\bar V^\gamma) =constant$
### 等熵(S)情況(補充) 
==$\bar V^RT^{C_\bar V}=constant$==

$S=\frac{Q}{T}\rightarrow dS=\frac{dQ}{dT}=0$
$\Rightarrow \frac{1}{T}(\frac{nRT}{\bar V}d\bar V+nC_VdT)$

$\Rightarrow nR\int \frac{d\bar V}{\bar V}+nC_V\int \frac{d\bar T}{\bar T}=0$

$\Rightarrow Rln\bar V+C_\bar VlnT=constant$

 $\Rightarrow \bar V^RT^{C_\bar V}=constant$
## 波 Wave
* ==Def==: 藉由++介質的擾動++(力學波)或++自身的移動++(非力學波)將能量, 動量傳遞下去
* 力學波
    * 1-D 繩波(弦波)
    * 2-D 水波
    * 3-D 在空氣中的聲波
* 非力學波
    * 電磁波
    * 機率波(物質波)

### 成因分類
* $\gamma$-ray
    * 核分裂
* x-ray
    * 煞車輻射
    * 高速電子撞擊金屬板, 瞬間減速$\rightarrow E_ke\rightarrow E=h\nu_{x-ray}$
* UV, VIS, IR
    * 熱輻射
    * 原子振動
* MW, RW
    * 電子在
        * 一段電線 :arrow_right: S.H.M
        * 一段線圈 :arrow_right: 等速圓周
    * 同步輻射
> [name=郭哲明][time=Wed, Mar 11, 2020 8:22 PM]
### 電磁波
* $\vec{E}=\vec{B}\times \vec{C}$
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/電磁波1.png)
> [name=郭哲明][time=Thu, Mar 12, 2020 6:10 PM]

![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/電磁波2.png)
* 波函數
    * $y_{x,t}=Rcos(kx\pm\omega t+\Phi)$
        * k(波數): $k\equiv \frac{2\pi}{\lambda}$
        * $\pm$(傳遞方向)
        * $\omega$(角速率): $\omega\equiv\frac{2\pi}{T}$
        * $\Phi$(相位角): 初始條件
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/電磁波3.png)
* 波速
    * 與介質種類與狀態有關
        * 繩波: 張力、粗細
        * 水波: 深度
        * 空氣中聲波: 溫度、濕度
* 介質的震動
    * 位置
    * 速度
        * 方向: 畫圖決定
        * 大小: 
            * 端點: u=0
            * 平衡點: $u_{max}$
    * u=v|切線斜率|
* $tan\theta =\frac{u}{v} \Rightarrow v \cdot tan\theta$
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/電磁波4.png)
> [name=郭哲明][time=Tue, Mar 17, 2020 12:25 PM]

* 介質的振動速度 **u**
    * $u=|\frac{dy}{dt}|=|\frac{dy}{dx}\times\frac{dx}{dt}|$=|切線速率$\times v$|
    * 繩波的傳遞速率\
    ![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/波1.png =300x300)
        * 線密度$\mu\equiv\frac{M}{L}$ $\Rightarrow dm=M\cdot dl=M\cdot R\cdot d\theta$
        * $d\theta\rightarrow 0: \sin d\theta\approx d\theta\approx \tan d\theta$
        * 合力$=2Fsin\frac{d\theta}{2}$
            * $=dm\cdot \frac{v^2}{R}=(\mu Rd\theta)\frac{v^2}{R}$
            * $\rightarrow F=\mu\cdot v^2$
            * $v=\sqrt{\frac{F}{\mu}}=f\cdot\lambda$
                * F: 鬆緊
                * $\mu$: 粗細
### 波的疊加(干涉)
* $\begin{cases}\vec{y}=\vec{y_1}+\vec{y_2}+\vec{y_3}+\vec{y_4}...\\\vec{u}=\vec{u_1}+\vec{u_2}+\vec{u_3}+\vec{u_4}...\end{cases}$
* 完全建設性(相長性)干涉\
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/波完全相長干涉.png =400x200)
* 完全破壞性(相消性)干涉\
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/波完全相消干涉.png =400x200)
* 反射
    * 固定端  
![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/波反射固定端.png =400x200)
    * 自由端  
    ![](https://github.com/chemmy-jack/hackmd2/raw/master/pics/波反射固自由端.png =400x200)
    * 粗細
        * 粗到細(似自由端反射)==missing==
        * 細到粗(似固定端反射)==missing==

#### 補充題目
繩波在粗細不同的繩中傳遞時，當振福y0的入射波傳遞至粗細繩之接點處時，會發生部分反射部分透射。若反射波的振幅為y1，透射波的振幅為y2，兩繩之線密度分別為$\mu_1 & \mu_2$，
試證: $y_1=\frac{\sqrt{\mu_1}-\sqrt{\mu_2}}{\sqrt{\mu_1}+\sqrt{\mu_2}}y_0$ ; $y_2=\frac{2\sqrt{\mu_1}}{\sqrt{\mu_1}+\sqrt{\mu_2}}y_0$。
1. 繩波的平均功率可視為波的強度:
    * $$\bar P=2\pi^2\cdot y_0^2\cdot f^2\cdot(\frac{F}{v})\propto I_0$$
    * 其中: F(張力), f(頻率)皆相同$\Rightarrow I_0\propto \frac{y_0^2}{v}$
    * 由**能量守恆**知:$I_0=I_1+I_2=\frac{y_0^2}{v_1}=\frac{y_1^2}{v_1}+\frac{y_2^2}{v_1}$

2. 波形是連續的
    * 在粗細繩知交接處:$\begin{cases}左:入射波與反射波的合成波形(=y_0+y_1)\\ 右:透射波的波形(=y_2)\end{cases}\\ \Rightarrow y_0+y_1=y_2$代回 1.
    * $\frac{y_0^2}{v1}=\frac{y_1^2}{v_1}+\frac{(y_0+y_1)^2}{v_2}\\ \Rightarrow v_2\cdot y^2=v_2\cdot y_1^2+v_1\cdot (y_0^2+2y_0y_1+y)\\ \Rightarrow (v_1+v_2)\cdot y_1^2+2v_1\cdot y_0\cdot y_1+(v_1-v_2)=1\\ \Rightarrow\begin{cases}y_1=\frac{v_2-v_1}{v_1+v_2}\cdot y_0\\ y_2=y_0+y_1=\frac{2v_2}{v_1+v_2}\cdot y_0\end{cases}$

3. $v=\sqrt{\frac{F}{\mu}}$代入:


### 相(位)差
* $\Delta P=\frac{\Delta X}{\lambda}=\frac{\Delta t}{T}=\frac{\Delta P}{2\pi}\begin{cases}\Delta X:波程差\\ \Delta t:時間差\\ \Delta \Phi :相位角差\end{cases} \\ \Rightarrow \Delta x=\Delta p\cdot \lambda\\ \begin{cases}完全建設性干涉\Delta P=0, \pm 1,\pm 2 ...\\ 完全破壞性干涉\Delta P=0, \pm \frac{1}{2},\pm \frac{1}{2} ... \end{cases}$
* $y_{(x,t)}=R\cdot \cos{(kx\pm \omega t+\Phi)}$
![](https://raw.githubusercontent.com/chemmy-jack/hackmd2/master/pics/%E7%9B%B8%E4%BD%8D%E5%B7%AE1.png)
* 完全建設性干涉
    * $\Delta x=n\cdot \lambda, (n\in Z)$
* 完全破壞性干涉
    * $\Delta x=(m-\frac{1}{2})\cdot \lambda, (m\in Z)$
#### 駐波
> [name=郭哲明][time=Tue, Mar 24, 2020 1:04 PM]
> 

$Y=y_1+y_2//=2R\cdot \cos kx \cdot \cos\omega t=R(x)\cdot S.H.M$
* 節點
$\Rightarrow R(x)=0\\ \Rightarrow$==missing==
* 腹點
$\Rightarrow |R_{(x))max} = 2R\\ \Rightarrow |2R\cdot coskx|=2R\\ \Rightarrow |coskx|=1$==missing==
### 水波

* $\frac{\sin(\theta_1)}{\sin(\theta_2)}=\frac{v_1}{v_2}=\frac{\lambda_1}{\lambda_2}=\frac{\sqrt{H_1}}{\sqrt{H_2}}$
* 水波繞射：波藉由+障礙物的缺口或邊緣+將能量繞傳至障礙物的後方
    ![](https://raw.githubusercontent.com/chemmy-jack/hackmd2/master/pics/水波繞射.png)
* 水波干涉$\begin{cases}完全波\\不完全波\end{cases}$
    * 兩個點波源
        * 同項==未==
            * nth目線$\Rightarrow \Delta x =\pm n\cdot \lambda$
            * nth節線$\Rightarrow$
        ![](https://raw.githubusercontent.com/chemmy-jack/hackmd2/master/pics/水波干涉1.png)
        ![](https://raw.githubusercontent.com/chemmy-jack/hackmd2/master/pics/水波干涉1板書.jpg)
        * $\Delta x= |\bar{PS_1}-\bar{PS_2}|\\=\begin{cases}n\cdot\lambda\end{cases}==未==
            * 某一條腹線
                * $|\overline{PS_1}-\overline{PS_1}|=n\cdot\lambda=(m-\frac{1}{2})\cdot\lambda$
                * P可能為
                    1. 直線(n=0)$\Rightarrow S_1,S_2$之中垂線
                    2. **雙曲線**
                    3. 分別由$S_1, S_2$向外延伸的射線$(n\lambda =\overline{S_1S_2})=(m-\frac{1}{2})\lmbda$
        * 反相