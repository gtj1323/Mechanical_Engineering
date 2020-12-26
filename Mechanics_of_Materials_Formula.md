[TOC]

# 1장 하중

##  1. 하중, 응력, 변형률

1. 하중 : 기계나 구조물이 외부로부터 받는 힘.

   1. 정하중 : 방향과 힘의 크기가 일정한 하중.

   2. 동하중 : 하중의 크기와 방향이 변하는 하중.

      > 반복하중 : 하중의 크기와 방향의 변화가 시간에 따라 일정한 반복을 하는 하중.
      > 교번하중 : 하중의 크기와 방향의 변화가 반복적이지 않은 하중.
      > 충격하중 : 짧은 시간에 급격히 작용하는 하중.

2. 응력 : 물체에 가해진 하중에 대한 저항력의 단위면적당 힘.

   1. 수직응력 : 면에 수직하게 작용하는 응력.
   2. 전단응력 : 면에 평행하게 작용하는 응력. 

3. 변형률 (Strain) : 변형전의 치수에 대한 변형량의 비.

   1. 종변형률 : 세로변형률, 수직응력에 의한 종방향 변형률.

   2. 횡변형률 : 가로변형률, 수직응력에 의한 횡방향 변형률.

   3. 전단변형률 : 각변형률, 전단응력에 의한 변형각도의 tangent값. (작기 때문에 각도와 거의 같은 값.)

   4. 체적변형률 : 변형전의 체적에 대한 체적변화량의 비. 종변형률의 3배와 비슷한 값을 가짐.

   5. 프와송의 비 (Poisson's ratio) ($\mu, \nu$)
      탄성한계 내에서 재료의 종병형률과 횡변형률의 비. ($\frac{1}{\mu}$프와송 수, $m\leqq2$)
   $\mu=\frac{횡변형률}{종변형률}$
      
      |       조건       | 설명                                     |
      | :--------------: | ---------------------------------------- |
      | $\nu$<0.5, $m<2$ | 현실. 탄성변형을 하면 체적이 감소.       |
      | $\nu$=0.5, $m=2$ | 탄성변형 중 체적이 일정한 조건.          |
      | $\nu$>0.5, $m>2$ | 탄성변형 중 체적이 커지는 조건. (불가능) |

4. 응력, 변형률, 파괴

   1. 탄성 (Elasticity) : 외력의 작용으로 변형이 일어나지만, 외력을 제거하면 원래대로 되돌아가려는 성질.
         $\sigma=E\varepsilon=\frac{P}{A}$
         $\lambda=\frac{Pl}{AE}$
   2. 소성 (Plasticity) : 외력의 작용으로 변형, 외력을 제거해도 되돌아가지 않고 영구변형하는 성질.
   3. 취성 (Brittleness) : 인성이 상실되어 충격하중이 극히 작음에도 재료의 파괴가 일어나는 현상.
   4. 비례한도 : 응력과 변형률이 직선비례관계를 가지는 한계응력.
   5. 탄성한도 : 잔류응력이 존재하지 않는 상한응력. 비례한도와 거의 같은 점.
   6. 변형경화 : Slip과 같은 재료의 소성변화를 통해 금속재료등의 강도가 증가하는 현상.
                       Dislocation의 증가와 얽힘 작용으로 인해 발생한다.
   7. 피로 : 반복,교번 하중에 의해 극한강도보다 더 작응 응력에 의해 파괴되는 현상.
                표면에 존재하는 작은 균열에 인장 잔류응력이 작용하여 균열이 확산되어 발생.
                표면에 피닝으로 압축 잔류응력을 만들어주어 개선 가능.
   8. 크리프(Creep) : 재료에 일정한 온도와 하중을 장시간 유지하면 변형이 일어나는 현상.
                                금속의 Grain Baundary가 서로 미끄러지는 현상으로 발생.
                                 Grain의 사이즈가 크거나 단결정 재료 사용으로 개선 가능. (단결정은 비쌈.)
   9. 바우싱거효과
      인장변형과 압축변형을 반복하면 반대방향의 항복강도가 작아지는 현상.

## 2. 힘

1. 라미의 정리(Lami's theorem)
   한 점에  $F_1, F_2, F_3$의 세 힘이 작용하고 있을 때, 세 점의 관계.
   ![99084E465CB99F6930](https://user-images.githubusercontent.com/43361320/102707575-ab0f9f00-42df-11eb-8647-4294dc3e5550.png)
   $\frac{F_1}{sin(\theta_1)}=\frac{F_2}{sin(\theta_2)}=\frac{F_3}{sin(\theta_3)}$
   
2. 탄성계수

   ※ 후크의 법칙(Hook's law) : 탄성한도 내에서 응력과 변형률은 비례한다는 법칙

   1. 종탄성계수 ($E$)
      비례한도 까지의 수직응력과 변형률의 비례상수.
   2. 전단탄성계수 ($G$)
      비례한도 까지의 전단응력과 변형률의 비례상수.
   3. 체적탄성계수 ($K$)
      비례한도 까지의 응력과 변형률의 비례상수.
   4. $E, G, K$의 관계
      $G=\frac{E}{2(1+\nu)}$, $K=\frac{E}{3(1-2\nu)}$
      $mE=2G(m+1)=3K(m-2)$
      $E=2G(1+\nu)=3K(1-2\nu)$

# 2장 재료의 정역학

## 1. 조합단면의 응력과 변형량

1. 직렬 조합
   전체 변형량 =  각 부분의 변형량의 합
   받는 하중은 모두 같음.
2. 병렬 조합
   전체 하중 = 각 부분이 받는 하중의 합
   변형량은 모두 같음.

## 2. 자중에 의한 변형

자중 : 재료 자체가 가진 중량.
자중에 의해 재료에 변형이 일어나기도 한다.
$\sigma_x=\frac{P+W_x}{A_x}$
$d\lambda=\frac{\sigma_x}{E}dx$

## 3. 열응력 (Thermal stress)

구속 상태의 재료에 온도변화를 통해 재료에 발생하는 응력.
가열끼워맞춤, 억지끼워맞춤의 원리.
열응력 : $\sigma=E\alpha(t_2-t_1)=E\alpha\Delta t$
열응력 : $\varepsilon=\alpha(t_2-t_1)=\alpha\Delta t$
열 변형량 : $\lambda=\varepsilon l = \alpha\Delta t l$ 

## 4. 탄성에너지(Elastic Energy)

응력이 탄성한계를 넘지 않는 범위에서 변형에너지.
$U=\frac{1}{2}P\lambda=\frac{P^2V}{2AE}=\frac{\sigma^2 V}{2E}$
$u=\frac{U}{V}=\frac{P^2}{2AE}=\frac{\sigma^2}{2E}=\frac{E\varepsilon^2}{2}=\frac{\varepsilon\sigma}{2}$

## 5. 충격에 의한 응력과 늘음량

위치에너지 : $E_p = W(h+\lambda)$
저장 가능한 탄성에너지 : $U=\frac{\sigma^2 A l}{2E}$
정하중에 의한 응력 : $\sigma_0=\frac{W}{A}$
정하중에 의한 늘음량 : $\lambda_0=\frac{Wl}{AE}=\frac{\sigma_0 \times l}{E}$

$E_p=U$연립
$\sigma=\sqrt{\frac{2EW(h+\lambda)}{Al}}=\sigma_0 \left ( 1+\sqrt{1+\frac{2h}{\lambda}} \right )$
$\lambda=\frac{\sigma l}{E}=\lambda_0 \left ( 1+\sqrt{1+\frac{2h}{\lambda}} \right )$

​                                                         충격계수 : $\left ( 1+\sqrt{1+\frac{2h}{\lambda}} \right )$

만약 $\lambda=0$이면,   $\sigma=\sqrt{\frac{2EWh}{Al}}$

만약 $h=0$이면,    $\sigma=2\sigma_0$, $\lambda=2\lambda_0$ (충격계수=2)

## 6. 압력을 받는 원통

1. 내압을 받는 얇은 원통
   원주방향 : $\sigma_1 = \frac{Pd}{2t}$
   축방향 : $\sigma_2 = \frac{Pd}{4t}$
2. 얇은 살두께의 구
   $\sigma=\frac{Pd}{4t}$

## 7. 얇은 회전체의 응력

각속도 $\omega=\frac{2\pi N}{60}[rad/s]$
원주속도 $v= r\omega[m/s]$
구심가속도(법선속도) $a_n=r\omega^2[m/s^2]$
원심력 $F=ma_n=mr\omega^2$
회전체 응력 $\sigma = \frac{\gamma v^2}{g}=\frac{\gamma r^2 \omega^2}{g}$

# 3장 응력의 조합상태

평면응력의 모어원(Mohr's Circle)
![images](https://user-images.githubusercontent.com/43361320/102708707-c7173e80-42e7-11eb-8305-5741fda60359.png)
x축 수직응력 : $\sigma_x$
y축 수직응력 : $\sigma_y$
전단응력 : $\tau_{xy}$
임의 경사각과  x,y축의 각도 차이 : $\theta$
임의경사각 수직응력 : $\sigma_n=\frac{1}{2}(\sigma_x+\sigma_y)+\frac{1}{2}(\sigma_x-\sigma_y)cos2\theta-\tau_{xy}sin2\theta$
임의경사각 전단응력 : $\tau=\frac{1}{2}(\sigma_x-\sigma_y)cos2\theta+\tau_{xy}sin2\theta$
주응력과 x,y축의 각도 관계 : $tan2\theta=-\frac{2\tau_{xy}}{\sigma_x-\sigma_y}$
수직응력 : $\sigma_{n,max}=\frac{1}{2}(\sigma_x+\sigma_y)\pm\frac{1}{2} \sqrt{(\sigma_x-\sigma_y)^2+4\tau_{xy}^2}$
최대 전단응력 : $\tau_{max} = \frac{1}{2} \sqrt{(\sigma_x-\sigma_y)^2+4\tau_{xy}^2}$
주변형률 : $\varepsilon_{n,max/min}=\frac{1}{2}(\varepsilon_x+\varepsilon_y)\pm\frac{1}{2} \sqrt{(\varepsilon_x-\varepsilon_y)^2+4\gamma_{xy}^2}$
최대 전단변형률 : $\gamma_{max} = \sqrt{(\varepsilon_x-\varepsilon_y)^2+4\gamma_{xy}^2}$

# 4장 평면도형의 성질

## 1. 단면 1차 모멘트와 도심

도심과 x축 거리 : $\bar{y}$ --- 관계식 : $\bar{y}A=\int _A ydA$
도심과 y축 거리 : $\bar{x}$ --- 관계식 : $\bar{x}A=\int _A xdA$

## 2. 단면 2차 모멘트

$I_x=\int _A y^2dA$
$I_y=\int _A x^2dA$

## 3. 평행축 정리(Parallel axis theorem)

단면 2차 모멘트를 $I_x$ 라고 할 때, 물체와 y축간의 거리를 $a$만큼 변했을 때, 단면 2차모멘트
$I_x'=I_x+a^2A$

## 4. 극단면 2차 모멘트(=극관성 모멘트 : Polar moment inertia)

$I_P=I_x+I_y$

## 5. 단면계수(Modulus of secton) $Z$

$Z_x=\frac{I_x}{e}$  $e$=최외각 거리

## 6. 극단면계쑤(Modulus of polar secton) $Z_P$

$Z_P=\frac{I_P}{e}$  $e$=최외각 거리

$O$을 도심으로 하는 2차단면 모멘트, 극관성 모멘트, 단면계수, 극단면계수
![img](https://user-images.githubusercontent.com/43361320/102709258-368f2d00-42ec-11eb-827a-245a7908e1d9.png)

# 5장 비틀림(Torsion)

## 1. 원형축의 비틀림

![download](https://user-images.githubusercontent.com/43361320/102709430-ed3fdd00-42ed-11eb-9443-8fa69abec676.jpg)

$tan\theta=\frac{r\theta}{l}=\frac{\tau}{G}$

## 2. $\tau$와 $T$의 관계

$\tau=\frac{Td}{2I_P}=\frac{Tr}{I_P}$
                                                                        암기 : $\tau=\frac{Gr\theta}{l}=\frac{Tr}{I_P}$

## 3. 전달동력

동력 $P = Fv = T\omega$
$1PS=75kg_fm/s$
$1kW=102kg_fm/s$

## 4. 비틀림 탄성에너지

$U=\frac{1}{2}T\theta=\frac{T^2l}{2GI_P}$
$u=U/V=\frac{\tau^2}{4G}$

## 5. 스프링

$k=\frac{P}{\delta}$
스프링의 최대 전단응력 $\tau_{max}=\frac{4P}{\pi d^2}+\frac{16PR}{\pi d^3}$
와알(Kwale)의 응력수정계수 : $K=\frac{4C-1}{4C-4}+\frac{0.615}{C}$ ($C=\frac{D}{d}$)
스프링의 처짐량 : $\delta=\frac{64nPR^3}{Gd^4}=\frac{8nPD^3}{Gd^4}$

# 6장 보(Beam)

## 1. 보(Beam)

1. 보(Beam)
   일반적으로 단면의 치수에 비해 길이가 긴 부재가 수직하중을 받기 위해 수평으로 지지된 구조물.
2. 정정보와 부정정보의 비교
   - 정정보(Statically Determinate Beam)
     정역학적인 평형방정식만으로 모든 미지수가 해결, 미지수의 반력이 3개.
     ex) 외팔보, 단순보, 돌출보
   - 부정정보(Statically Indeterminate Beam)
     정역학적 평형방정식만으로는 모든 미지수의 해결이 불가능. 보의 처짐을 고려한 경계조건을 세워 미지수를 해결. 반력이 3개 초과하여 존재.
     ex) 일단 고정 타단지지보, 양단 고정보, 연속보 등

## 2. 보의 전단력 선도와 굽임 모멘트 선도

1. 전단력 선도(Shearing Force Diagram : S.F.D)
   전단력의 크기를 선도상으로 나타낸 것.
2. 굽힘모멘트 선도(Bending Moment Diagram : B.M.D)
   굽힘모멘트의 크기를 나타낸 것.

S.F.D를 거리에 따라 적분하면 B.M.D가 됨.

![ebb3b4ec9d98-ecb298eca790eab081-ebb08f-ecb59ceb8c80ecb298eca790-eab3b5ec8b9d](https://user-images.githubusercontent.com/43361320/102709946-2f6b1d80-42f2-11eb-82fa-728fc5599e82.jpg)

| 보                         | $M_{max}$        | $\sigma_{max}$      | $\theta_{max}$                                               | $\delta_{max}$                                               |
| -------------------------- | ---------------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 켄틸레버보<br />집중하중   | $Pl$             | $\frac{M_{max}}{Z}$ | $\frac{Pl^2}{EI}$                                            | $\frac{Pl^3}{3EI}$                                           |
| 켄틸레버보<br />우력       | -                | $\frac{M_{max}}{Z}$ | $\frac{Ml}{EI}$                                              | $\frac{Ml^2}{2EI}$                                           |
| 켄틸레버보<br />분포하중   | $\frac{wl^2}{2}$ | $\frac{M_{max}}{Z}$ | $\frac{wl^3}{6EI}$                                           | $\frac{wl^4}{8EI}$                                           |
| 단순보<br />C점 집중하중   | $\frac{Pab}{l}$  | $\frac{M_{max}}{Z}$ | $\theta_A=\frac{Pab(l+b)}{6lEI}$<br />$\theta_B=\frac{Pab(l+a)}{6lEI}$ | $\frac{Pa^2b^2}{3lEI}$                                       |
| 단순보<br />집중하중(중앙) | $\frac{Pl}{4}$   | $\frac{M_{max}}{Z}$ | $\frac{Pl^2}{16EI}$                                          | $\frac{Pl^2}{48EI}$                                          |
| 단순보<br />분포하중       | $\frac{wl^2}{8}$ | $\frac{M_{max}}{Z}$ | $\frac{wl^3}{24EI}$                                          | $\frac{5wl^4}{384EI}$                                        |
| 단순보<br />A점 우력       | -                | $\frac{M_{max}}{Z}$ | $\theta_A=\frac{Ml}{3EI}$<br />$\theta_B=\frac{Ml}{6EI}$     | $\delta_{max}\frac{Ml^2}{9\sqrt{3}EI}$ B점에서 $\frac{l}{\sqrt3}$<br />$\delta_{c}=\frac{Ml^2}{6EI}$ |
| 단순보<br />양단우력       | -                | $\frac{M_{max}}{Z}$ | $\theta_A=\frac{Ml}{2EI}$                                    | $\frac{Ml^2}{8EI}$                                           |

# 7장 보 속의 응력

## 1. 보속의 굽힘응력

$\rho$ : 중립축의 곡률반경 ($\frac{1}{\rho}$ =곡률)
$y$ : 중립축으로부터 떨어진 임의의 거리 ($y_{max}=e$)
$\varepsilon$ : 임의의 거리 $y$에서 굽힘에 의한 변형률($\varepsilon=\frac{\sigma}{E}=\frac{y}{\rho}$)

$\frac{1}{\rho}=\frac{M}{EI}=\frac{\sigma}{Ey}$            $\sigma = \frac{My}{I} = \frac{M}{Z}$

# 8장 보의 처짐

## 1. 처짐곡선(=탄성곡선의 미분방정식)

$y=\delta$처짐량
처짐곡선(=탄성곡선)의 미분 방정식 : $EI\frac{d^2y}{dx^2}=-M$
$EI\frac{d^3y}{dx^3}=-F$
$EI\frac{d^4y}{dx^4}=-w$
$\frac{dy}{dx}=\theta$(처짐각)

$EIy=-\iint Mdxdx + C_1x +C_2$ (양단의 초기값을 이용해서 $C_1$, $C_2$를 구함.)

## 2. 면적모멘트법(Area moment method)

1. 처짐각
   $dS=\rho d\theta$ 이고, $\frac{1}{\rho}=\frac{d\theta}{dS}=\frac{d\theta}{dx}=\frac{M}{EI}$
   $d\theta = \frac{Mdx}{EI} = \frac{dA_M}{EI}$
   따라서 $\int \limits_A^B d\theta = \int \limits_A^B  \frac{dA_M}{EI}$, $\theta = \frac{A_M}{EI}$       Mohr의 제1 정리, 제 1 면적모멘트법
2. 처짐량
   $y:dx=d\delta:(x+dx)$, 임을 통해서, $d\delta =  \frac{y(x+dx)}{dx} = \frac{dx \cdot d\theta (x+dx)}{dx} = xd\theta +d\theta dx \fallingdotseq xd\theta=\frac{xdA_M}{EI}$
   $\int \limits_A^B d\delta=\int \limits_A^B \frac{xdA_M}{EI}$
   $\delta=\frac{A_M}{EI}\bar{x}=\theta\bar{x}$

$A_M$ : B.M.D 면적
$\bar{x}$ :처짐을 구하고자 하는 위치로부터 B.M.D의 도심점까지 거리
$\theta$ : 처짐 각

## 3. 중첩법(=겹침법 : Method of superposition)

집중하중, 분포하중을 동시에 받으면 각각을 계산하여 합산함

# 9장 부정정보

## 1. 부정정보

정역학적 평형조건으 풀 수 없는 보. 과잉구속조건을 가진 보.

## 2. 부정정보 종류

1. 일단고정, 타단 지지보(한쪽 고정, 한쪽 지지)
2. 양단 고정보 (양쪽 고정)
3. 공식 정리
   ![부정정보 공식](https://user-images.githubusercontent.com/43361320/103146956-9de92900-4793-11eb-9c57-233340517bf7.png)

# 10장 기둥(Column)

## 1. 편심하중을 받는 단주

$\sigma_{max}=\sigma_1 +\sigma_2 = \frac{P}{A} + \frac{M}{Z_1}$
$\sigma_{min}=\sigma_1 +\sigma_2 = \frac{P}{A} - \frac{M}{Z_1}$

## 2. 장주(Long Column)

1. 세장비(Slenderness Ratio)($\lambda$)
   기둥의 가느다란 정도를 나타내는 척도
   $\lambda = \frac{l}{K}$
   $l$ : 기둥의 길이
   $K$ : 기둥의 최소회전반경(=최소 단면 2차 반지름) $K_{min} = \sqrt{\frac{I_{min}}{A}}$

   | 재료              | 목재 | 주철 | 경강 | 연강 | 연철 |
   | ----------------- | ---- | ---- | ---- | ---- | ---- |
   | 세장비($\lambda$) | <80  | <70  | <95  | <102 | <115 |

2. 오일러의 공식(Euler's Foumula)
   좌굴하중 $P_B = n\pi ^2\frac{EI_{min}}{l^2}$
   좌굴응력 $\sigma_B = \frac{P_B}{A} = n\pi ^2\frac{EI_{min}}{Al^2} = n\pi ^2\frac{EK^2}{l^2} = n\pi ^2\frac{E}{\lambda^2}$
   $n$ : 단말계수
   좌굴세장비(=유효세장비) $\lambda_e=\frac{\lambda}{\sqrt{n}}$
   ![보](https://user-images.githubusercontent.com/43361320/103147324-9297fc80-4797-11eb-9a80-ce8c93ae49ef.png)