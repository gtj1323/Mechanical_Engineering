[TOC]

# 1. 유체의 정의 및 성질

## 1. 유체의 정의와 분류

1. 유체의 정의
   작은 전단력이라도 저항하지 못하고 계속해서 변형하는 물질.
   액체와 기체가 여기에 해당.
2. 유체의 분류
   - 압축성유체
     압력변화에 대해 밀도, 비중량, 체적 등의 변화를 무시할 수 없는 유체. 기체.
   - 비압축성유체
     압력변화에 대해 밀도, 비중량, 체적 등의 변화를 무시할 수 있는 유체. 액체.
   - 점성유체
     점성을 갖고 있는 모든 유체. 실제로 존재하는 모든 유체.
   - 비점성유체
     점성을 무시할 수 있는 유체.
   - 이상유체
     점성, 비압축성 유체.
   - 뉴톤유체
     뉴톤의 점성법칙을 만족, 끈기를 가진 유체. (진흙, 플라스틱, 타르 등)
   - 탄성유체
     압축에 의해서 저장된 탄성에너지를 압력을 제거하면 본래 상태로 팽창되어 되돌아오는 유체.
     체적탄성계수 ($K$)=$\infin$

## 2. Newton의 점성법칙

점성(viscosty) : 유체가 서로 인접하고 있는 층 사잉에 상대운동이 발생할 때 이 상대운동을 방해하는 유체마찰.

![점성법칙](https://lh3.googleusercontent.com/proxy/UOyfa0wune1PJbEoVL6TrGxfqaUafT7fPcmxkVAhmBz7wOjrHjfP6s-ucCmkLliprO7H8Qu8DCo7nLA7KlpEo79RSRgPGR2c5DyPHtCYvTPZHjDkwpqZ0D2Rd237SfACR1Ad-QZojE8gglJlt_zkn1Yf8uScMFL_BEvI3nLe-aBeIA-GkV7eLg1mWwrZatMwYWNTjrFbWFAE63PVFObQUMhaZ3YF_ap4kn78iKFZq3mDZKjTpiOQw9IEJZoERdcvIXLuDEwcMm3eISjaDFz-Mt_NQo3rTWjeHjCILII-eCNpnWm-z3Q)

1. 점성계수
   유체의 점성을 유체의 값. 온도, 농도 등의 영향을 받음.
   $F= \mu \frac{uA}{y}$  $\mu$ :  점성계수 [$Pa \sdot s$]  [$N \sdot s / m^2$]
   $\tau = \mu \frac{du}{dy}$
2. 동점성계수
   점성계수를 유체의 밀도로 나눈 값.
   $\nu = \frac{\mu}{\rho}$       $\nu$ : 동점성계수 [$m^2/s$]
   $1strokes = 1cm^2/sec = 10^{-4}m^2/s$

## 3. 체적탄성계수 (K,E)[$N/m^2$]

$K = \frac{\Delta p}{-\frac{\Delta V}{V}} = \frac{\Delta p}{\frac{\Delta \gamma}{\gamma}} = \frac{\Delta p}{\frac{\Delta \rho}{\rho}}$
$\Delta p = $유체에 추가적으로 가해진 압력
$V=$유체의 초기 체적
$\Delta V=$유체의 체적 변화량
압축률 $\beta=\frac{1}{K}$

## 4. 음속

음속($a$) = 전파 속도

$a=\sqrt {\frac{dp}{d \rho}}=\sqrt {\frac{g dp}{d \gamma}}$

1. 액체속 음속
   $K=p$ 만족
   $a = \sqrt {\frac{dp}{d \rho}} = \sqrt {\frac{g dp}{d \gamma}} = \sqrt {\frac{Kg}{d \gamma}} = \sqrt {\frac{K}{\rho}} = \sqrt {\frac{1}{\beta \rho}}$
2. 공기중(=대기)에서의 음속
   $K=kp$ 만족
   $a = \sqrt {\frac{dp}{d \rho}} = \sqrt {\frac{g dp}{d \gamma}} = \sqrt {\frac{kgp}{\gamma}} = \sqrt{kRT}$

## 5. 표면장력과 모세관 현상

1. 표면장력($\sigma$ : surface tension) [$N/m^2$]
   유체는 분자간의 인력으로 평형상태를 유지한다. 그리고 유체의 자유표면은 외부로부터 힘을 받지 않기 때문에 둥근 형태를 유지하려고 하는데 이 힘을 표면장력이라한다.

   구형 물방울의 표면 장력 $\sigma = \frac{\Delta pd}{4}$     $\Delta p $ : 물방울 내부와 외부의 압력차

2. 모세관 현상
   액체에 가는 관을 세우면 액체가 관을 따라 상승 혹은 하강한다. 이 현상을 모세관 현상이라 한다. 이때 관의 기울기와 상관없이 상승하거나 하강한 액면의 높이는 일정하다.

   관의 액면 상승 높이 $h = \frac{4 \sigma cos(\beta)}{\gamma d}$

   $\beta$ : 액면 접촉각($\deg$)

   두 평판의 거리를 b로 한 경우 액면 상승 높이 $h = \frac{2 \sigma cos(\beta)}{\gamma b}$

# 2. 유체 정역학

## 1. 정지유체

__정지유체의 기본 성질__

> 1. 정지유체내의 임의의 한 점에 작용하는 압력의 크기는 모든 방향에서 동일하다.
> 2. 정지유체내의 압력은 모든 면에 수직으로 작용한다.
> 3. 밀폐된 용기 속 유체에 가한 압력은 모든 방향에서 같은 크기로 전달된다. (파스칼의 원리)
> 4. 동일 수평상에 있는 두 점의 압력의 크기는 같다.

- 파스칼의 원리
  밀폐된 용기 속 유체에 가한 압력은 모든 방향에서 같은 크기로 전달된다.
  수압기의 원리 (압력이 같으므로 면적이 다르면 힘의 크기가 다르다. )

## 2. 정지유체내의 압력변화

 정지유체 내의 압력은 위치의 고저에 따라 달라진다. (해수면에서 깊은 곳의 압력이 높음.) 이를 이용해서 액주계를 통해 유체의 압력을 계산할 수 있다.
$p=\rho g h=\gamma h$

## 3. 평면에 작용하는 유체의 전압력

 유체는 위치의 고저에 따라 달라지기 때문에 이를 고려하여 계산을 통해서 평면에 작용하는 유체의 전압력을 구해야한다.
![121231231`23](https://user-images.githubusercontent.com/43361320/84116549-04faf680-aa6b-11ea-89a8-ad90f925687b.png)

$G$ : 평판의 도심
$C$ : 작용점
$z_p = z_g + \frac{I_G}{Az_g}$ : 작용점까지의 거리
$h_p =z_p sin \theta$ : 작용점의 깊이
$F = \gamma h_g A$

## 4. 곡면에 작용하는 유체의 전압력

곡면에 작용하는 유체의 전압력은 수평성분($F_x, F_H$)과 수직성분($F_y, F_V$)으로 나누어 고려해야한다.
$F_H=\gamma \overline h A$
$F_V=$연직 상방향에 실린 액체의 무게과 같음. 혹은 실릴 수 있는 액체의 무게와 같음.
$F = \sqrt{F_H^2 + F_V^2}$

## 5. 부력

정지유체 속에서 잠겨있거나 떠있는 무체가 유체로부터 받는 수직상방향 힘. 아르키메데스에 의해 적립됨.
$F_B = \gamma_{liq} V$          $\gamma_{liq} : 액체의 비중량$     $V : 물체의 잠겨있는 부분의 체적$
![](data:image/jpeg;base64,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)

|                                    |                             |                             |
| ---------------------------------- | --------------------------- | --------------------------- |
| $\overline{MC}>0$: 안정            | $\overline{MC}<0$: 안정     | $\overline{MC}=0$: 안정     |
| 물체가 기울면 원래의 위치로 돌아옴 | 물체가 기울면 계속해서 기움 | 물체가 새로운 위치에서 정지 |
| M이 C보다 위에 있음                | M이 C보다 아래 있는 경우    | M과 C가 같은 지점           |

$B$ : 부력중심
$C$ : 무게중심
$W$ : 부양체 중심
$F_B$ : 부력
M : 경심. 이동한 부력중심점을 통과하는 수직선과 부양축과의 교점.
$\overline{MC}$ : 경심고(경심 높이)

## 6. 등가속도 운동을 받는 유체(=상대평형)

1. 수평 등가속도($a_x$) 운동을 받는 유체
   ![수평 등가속도 운동 유체](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/%EC%83%81%EB%8C%80%EC%A0%95%EC%A7%80.png/400px-%EC%83%81%EB%8C%80%EC%A0%95%EC%A7%80.png)
   $h$ : 운동을 하지 않을 때 수평면 높이
   $H$ : 운동을 할 때 수평면의 최대 높이
   $\theta$ : 액면경사각
   $tan \theta = \frac{a_x}{g}$

2. 연직 등가속도($a_y$) 운동을 받는 유체
   $p_1$ : 유체 내 임의의 위치의 압력
   $p_2$ : $p_1$보다 h만큼 아래에 위치한 유체 내의 압력
   $p_2 - p_1 = \gamma h \left ( 1+\frac{a_y}{y} \right )$

3. 등속회전 운동을 받는 유체 (각속도 $\omega$)
   ![등속회전 유체](![등속회전 유체](https://user-images.githubusercontent.com/43361320/84125797-0da5f980-aa78-11ea-9906-d48685900d90.png)
   중심에서 r만큼 떨어진 위치에서 유체가 받는 수평방향 가속도 : $r\omega ^2$
   $h$=수면 최고높이나 최저높이의 차이
   $h_r$=임의의 한 점에서 수면의 높이
   $h_r =\frac{r^2\omega^2}{2g}$
   $h=\frac{R^2\omega^2}{2g}$

   $\omega = \frac{\sqrt {2gh}}{r}$

   $p = p_0 + \gamma h_r$     $p_0$ : 같은 액면 상의 중심 압력

   정지상태 수면과 최고수면 사이의 관계도 봐 둘 것.