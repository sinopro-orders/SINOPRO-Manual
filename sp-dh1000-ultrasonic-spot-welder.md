# SP-DH1000 Ultrasonic spot welder

> **SINOPRO** · 문서 번호 SINOPRO-M-SP-DH1000 · Rev. 1.0 · 2026. 08.

![SP-DH1000](.gitbook/assets/imagesimage1.png)

{% hint style="info" %}
본 설명서에 기재된 장비는 엄격한 품질 및 제조 기준에 따라 제작되었습니다.

출고 전 충분한 테스트와 검수를 완료하였으며, 본 설명서에 명시된 절차에 따라 올바르게 사용할 경우 장기간 안전하고 안정적인 성능을 유지할 수 있습니다.

장비를 사용하기 전 **「2. 안전 및 주의사항」의 내용을 반드시 확인해야 합니다.**
{% endhint %}

## 1. 장치 정보

### 1-1. 장치 개요

**초음파란?**

초음파는 인간의 가청 범위 상한을 초과하는 주파수의 기계적 진동입니다. 일반적으로 **18kHz(18,000Hz)** 이상의 주파수를 초음파라고 하며, 사람의 귀에는 들리지 않습니다.

**초음파 용접의 원리**

초음파 용접의 기본 원리는 전기 에너지를 기계적 진동으로 변환하는 것입니다. 고주파 전기 에너지가 고주파 기계 진동으로 변환되고, 이 진동이 가압 상태의 금속 공작물 접합면에서 마찰열을 발생시킵니다. 이 열에 의해 모재를 녹이지 않고 고상 야금 접합이 이루어져, 용접이 완성됩니다.

**초음파 시스템 구성**

초음파 용접 시스템은 다음의 주요 부품으로 구성됩니다:

* 구동 제어함 (Drive control box)
* 증폭봉 (Booster)
* 트랜스듀서 (진동자, Transducer)
* 용접 헤드 (Welding horn)
* 공압 작동 장치 및 고정 지그

### 1-2. 장치 구성

**본체 정면 — 초음파 웰딩기 제어 화면 설명**

![본체 정면](.gitbook/assets/imagesimage4.jpeg)

<table><thead><tr><th width="77" align="center">번호</th><th width="208">명칭</th><th>설명</th></tr></thead><tbody><tr><td align="center">1</td><td>발생기 본체 전원 스위치</td><td>이 버튼을 통해 본체의 전원을 켜고 끌 수 있습니다.</td></tr><tr><td align="center">2</td><td>영문 전환 버튼</td><td>이 버튼을 누르면 사용자 인터페이스를 영어 화면으로 전환할 수 있습니다.</td></tr><tr><td align="center">3</td><td>파라미터 설정 버튼</td><td><p>이 버튼을 누르면 비밀번호를 입력하여 파라미터 설정 화면으로 진입할 수 있습니다. </p><p>파라미터 설정 관련 내용은 그림 4를 참조해 주십시오. </p><p>※ 초기 비밀번호는 8888입니다.</p></td></tr><tr><td align="center">4</td><td>중문 전환 버튼</td><td>이 버튼을 누르면 사용자 인터페이스를 중국어 화면으로 전환할 수 있습니다.</td></tr><tr><td align="center">5</td><td>USB 출력 포트</td><td>USB 포트를 통해 각 용접 작업의 상세 데이터를 추출할 수 있습니다.</td></tr></tbody></table>

**디스플레이 항목 설명**

<div data-with-frame="true"><img src=".gitbook/assets/imagesimage5 (1).jpeg" alt="디스플레이 항목"></div>

<table><thead><tr><th width="79.25" align="center">번호</th><th>화면 표시</th><th>항목명</th><th align="center">설정 가능 여부</th><th width="274.25">기능 및 사용 방법</th><th>검수 시 참고값</th></tr></thead><tbody><tr><td align="center"><strong>1</strong></td><td>MODE</td><td>운전 모드</td><td align="center">●</td><td><strong>Automatic(자동) / Mould(금형 조정)</strong> 모드를 선택합니다. 일반 용접 작업 시 Automatic 모드를 사용하며, 금형 교체 및 조정 시 Mould 모드를 사용합니다.</td><td>Automatic</td></tr><tr><td align="center"><strong>2</strong></td><td>Amplitude</td><td>전류/출력 표시</td><td align="center">×</td><td>장비 작동 시 실제 출력 상태를 표시하는 값으로 사용자가 설정할 수 없습니다. </td><td>-</td></tr><tr><td align="center"><strong>3</strong></td><td>Power</td><td>실제 출력</td><td align="center">×</td><td>용접 시 실제 출력값을 표시합니다. 단위는 <strong>W</strong>이며 사용자가 설정할 수 없습니다.</td><td>-</td></tr><tr><td align="center"><strong>4</strong></td><td>Energy</td><td>실제 에너지</td><td align="center">×</td><td>1회 용접 시 실제 출력된 에너지값을 표시합니다. 단위는 <strong>J</strong>이며 사용자가 설정할 수 없습니다.</td><td>-</td></tr><tr><td align="center"><strong>5</strong></td><td>Time</td><td>실제 용접 시간</td><td align="center">×</td><td>1회 용접 시 실제 초음파 출력 시간을 표시합니다. 단위는 <strong>s</strong>이며 사용자가 설정할 수 없습니다.</td><td>-</td></tr><tr><td align="center"><strong>6</strong></td><td>Frequency</td><td>실제 주파수</td><td align="center">×</td><td>장비 작동 시 자동으로 추적된 실제 주파수를 표시합니다. 단위는 <strong>kHz</strong>이며 사용자가 설정할 수 없습니다.</td><td>-</td></tr><tr><td align="center"><strong>7</strong></td><td>Production Number</td><td>생산 수량</td><td align="center">×</td><td>작업이 1회 완료될 때마다 수량이 자동으로 1씩 증가합니다.</td><td>-</td></tr><tr><td align="center"><strong>8</strong></td><td>Freq Scanning</td><td>주파수 스캔</td><td align="center">버튼</td><td>발진기, 진동자 및 혼 간의 주파수를 자동으로 보정 및 매칭하는 기능입니다. 혼 교체 후 또는 주파수 매칭이 필요한 경우 사용합니다.</td><td>검수 시 실행</td></tr><tr><td align="center"><strong>9</strong></td><td>Mould</td><td>금형 조정</td><td align="center">버튼</td><td>금형 교체 또는 혼/금형 위치 조정 시 사용합니다. 조정 중 초음파가 잘못 출력되는 것을 방지합니다.</td><td>-</td></tr><tr><td align="center"><strong>10</strong></td><td>Automatic</td><td>자동</td><td align="center">버튼</td><td>일반 용접 작업 시 자동 운전 모드로 전환합니다.</td><td>-</td></tr><tr><td align="center"><strong>11</strong></td><td>Sonic Test</td><td>초음파 테스트</td><td align="center">버튼</td><td>초음파 출력 여부를 테스트하고 전류 및 주파수 상태가 정상인지 확인합니다.</td><td>-</td></tr><tr><td align="center"><strong>12</strong></td><td>Clear</td><td>카운트 초기화</td><td align="center">버튼</td><td>Production Number의 생산 수량을 초기화합니다.</td><td>-</td></tr><tr><td align="center"><strong>13</strong></td><td>Reset</td><td>리셋</td><td align="center">버튼</td><td>장비 과부하 또는 알람 발생 시 알람을 해제하고 장비를 리셋합니다.</td><td>-</td></tr><tr><td align="center"><strong>14</strong></td><td>Amplitude</td><td>진폭</td><td align="center">●</td><td>초음파 출력의 진폭을 설정합니다. 용접 소재 및 용접 상태에 따라 조정하며, 변경 시 낮은 값부터 단계적으로 조정합니다.</td><td><strong>50%</strong></td></tr><tr><td align="center"><strong>15</strong></td><td>Shake time</td><td>진락 시간</td><td align="center">●</td><td>용접 완료 후 초음파를 한 번 더 출력하여 용접물이 혼에 달라붙는 현상을 방지합니다. 실제 용접 상태에 따라 조정합니다.</td><td><strong>0.050 s</strong></td></tr><tr><td align="center"><strong>16</strong></td><td>Cooling time</td><td>냉각/유지 시간</td><td align="center">●</td><td>초음파 출력이 완료된 후 혼이 용접물을 누른 상태로 유지되는 시간을 설정합니다.</td><td><strong>0.000 s</strong></td></tr><tr><td align="center"><strong>17</strong></td><td>Welding energy / Welding time</td><td>용접 에너지 / 용접 시간</td><td align="center">●</td><td><strong>Energy mode</strong>에서는 <code>Welding energy</code>가 표시되며 목표 용접 에너지(J)를 설정합니다. <strong>Time mode</strong>에서는 <code>Welding time</code>이 표시되며 초음파 출력 시간(s)을 설정합니다. 소재 및 실제 용접 상태에 따라 조정합니다.</td><td><strong>Energy mode: 6 J</strong></td></tr><tr><td align="center"><strong>18</strong></td><td>Delay time</td><td>지연 시간</td><td align="center">●</td><td>혼이 하강한 후 초음파 출력이 시작되기까지의 대기 시간을 설정합니다. 실제 용접 조건에 따라 조정합니다.</td><td><strong>0.150 s</strong></td></tr><tr><td align="center"><strong>19</strong></td><td>Welding mode</td><td>용접 모드</td><td align="center">●</td><td><strong>Energy mode(에너지 모드) / Time mode(시간 모드)</strong> 중 선택합니다. 선택한 모드에 따라 17번 항목이 Welding energy 또는 Welding time으로 변경됩니다.</td><td><strong>Energy mode</strong></td></tr></tbody></table>

**용접 헤드**

![용접 헤드](.gitbook/assets/imagesimage6.jpeg)

<table><thead><tr><th width="81.5" align="center">번호</th><th width="286.75">구성품명</th><th>기능 및 설명</th></tr></thead><tbody><tr><td align="center">1</td><td><strong>에어 실린더</strong> </td><td>에어 공급 시 용접 혼을 상·하로 구동합니다. 용접 혼의 하강 스트로크를 조정할 수 있습니다.</td></tr><tr><td align="center">2</td><td><strong>솔레노이드 밸브</strong> </td><td>본체와 연결되어 에어 실린더의 상승·하강 동작을 제어합니다. 또한 실린더로 공급 및 배출되는 에어 유량을 조절할 수 있습니다.</td></tr><tr><td align="center">3</td><td><strong>에어 레귤레이터</strong></td><td>에어 공급 라인이 연결되는 부분으로, 공급되는 에어 압력을 조절합니다. 또한 필터를 통해 압축공기에 포함된 수분을 제거합니다.</td></tr><tr><td align="center">4</td><td><strong>용접 혼</strong> </td><td>용접 대상물에 초음파 진동을 전달하여 실제 용접이 이루어지는 부분입니다. 사용 주파수에 따라 <strong>20 kHz / 25 kHz / 35 kHz / 40 kHz</strong> 등으로 구분되며, 용접 조건 및 대상물에 따라 다양한 형상의 혼을 사용할 수 있습니다. <strong>(그림 B 참조)</strong></td></tr><tr><td align="center">5</td><td><strong>하부 금형 블록</strong> </td><td>용접 대상물을 받쳐주는 하부 금형 구성품으로, 용접 대상물의 형상 및 사양에 따라 다양한 형태로 적용할 수 있습니다. <strong>(그림 A 참조)</strong></td></tr><tr><td align="center">6</td><td><strong>하부 금형 고정 지그</strong></td><td>하부 금형 및 용접 대상물을 지정된 위치에 고정하기 위한 지그입니다. 작업 조건 및 대상물에 따라 다양한 형상으로 적용할 수 있습니다. <strong>(그림 A 참조)</strong></td></tr><tr><td align="center">7</td><td><strong>상승 스트로크 조절 나사</strong> </td><td>용접 혼의 상승 위치 및 상승 스트로크를 조정합니다.</td></tr><tr><td align="center">8</td><td><strong>진동자 고정 나사</strong> </td><td>용접 혼 및 진동자 조립부를 고정합니다. 해당 나사를 풀어 용접 혼의 용접면 방향을 변경하거나 혼을 교체할 수 있습니다.</td></tr><tr><td align="center">9</td><td><strong>진동자 연결 커넥터</strong> </td><td>초음파 발진기(본체)와 진동자를 연결하는 커넥터입니다.</td></tr><tr><td align="center">10</td><td><strong>솔레노이드 밸브·팬 연결 커넥터</strong></td><td>발진기와 연결하여 솔레노이드 밸브 구동 및 냉각 팬 전원을 공급하는 커넥터입니다. <strong>※ 팬 사용 전원: AC 220 V</strong></td></tr><tr><td align="center">A</td><td>하부 금형 및 지그</td><td>용접 대상물의 형상 및 사양에 따라 다양한 형태의 하부 금형 및 고정 지그를 적용할 수 있습니다.</td></tr><tr><td align="center">B</td><td>용접 혼</td><td>용접 소재, 형상 및 용접 조건에 따라 다양한 형상의 용접 혼을 적용할 수 있습니다.</td></tr></tbody></table>



{% hint style="warning" %}
⚠ 팬은 **220V** 사용 주의합니다.
{% endhint %}

**본체 뒤면**

![본체 뒤면](.gitbook/assets/imagesimage7.jpeg)

<table><thead><tr><th width="70" align="center">번호</th><th width="281">명칭</th><th>설명</th></tr></thead><tbody><tr><td align="center">1</td><td>풋 스위치 포트</td><td>풋 스위치를 연결하는 단자입니다. 이 단자는 자동 공급 장치에서 메인 장치로 트리거 신호를 보내는 역할도 겸합니다.</td></tr><tr><td align="center">2</td><td>전원 케이블 포트</td><td>전원 케이블을 연결하는 포트입니다. 입력 전원은 기본적으로 AC 220V를 사용합니다.</td></tr><tr><td align="center">3</td><td>퓨즈 (15A)</td><td>기기를 보호하는 역할을 하며, 과전류 또는 과부하 시 회로 차단 기능을 합니다.</td></tr><tr><td align="center">4</td><td>트랜스듀서 포트 (진동자 연결 포트)</td><td>초음파 트랜스듀서(진동자)를 연결하는 9핀 커넥터 포트입니다.</td></tr><tr><td align="center">5</td><td>냉각 팬</td><td>장비 내부의 발열을 줄이기 위한 방열 팬입니다.</td></tr><tr><td align="center">6</td><td><p>솔레노이드 밸브 팬 포트 </p><p>(전자밸브 연결 포트)</p></td><td>솔레노이드 밸브를 연결하는 10핀 커넥터 포트입니다.</td></tr></tbody></table>

{% hint style="danger" %}
⚠️ **주의**: 이 포트에는 **220V 전원**이 공급되므로, 설치 또는 점검 시 반드시 **전원을 차단한 상태**에서 작업해야 합니다.
{% endhint %}

**기본 제공 부속품**

| 품목     |  수량 |
| ------ | :-: |
| 10A 퓨즈 |  2  |
| 육각 렌치  |  2  |
| 풋 스위치  |  1  |

### 1-3. 장치 사양 및 규격&#x20;

<table><thead><tr><th width="242">항목</th><th>본문 참고 수치</th></tr></thead><tbody><tr><td>출력</td><td>800W</td></tr><tr><td>초음파 주파수</td><td>40 kHz ±0.15 kHz</td></tr><tr><td>입력 전압</td><td>AC 220V/ 50Hz/ 60Hz</td></tr><tr><td>용접 시간 정밀도</td><td>0.001 s</td></tr><tr><td>출력 조절 방식</td><td>무단 연속 조절 + 지능형 정출력 제어</td></tr><tr><td>에너지 변환 효율</td><td>≥92%</td></tr><tr><td>역률</td><td>≥0.95</td></tr><tr><td>장비 운전 소음</td><td>＜75 dB</td></tr><tr><td>압력 조절 범위</td><td>0~1 Mpa 조절 가능</td></tr><tr><td>시간 조절 범위</td><td>0~60s 조절 가능</td></tr><tr><td>1회 용접 시간</td><td>≤0.5 s</td></tr><tr><td>진폭 조절 범위</td><td>10~100%</td></tr><tr><td>품질 관리 기능</td><td>주파수, 출력, 에너지, 진폭 상한·하한 초과 시 경보 및 장비 정지</td></tr></tbody></table>

#### 고객 용접 공정 요구사항 및 제품 적용 사양

본 장비는 신에너지 배터리 셀 용접 공정에 맞춰 설계되었으며, 권취형(Jelly Roll) 및 적층형(Stacking) 셀의 양극·음극 용접에 적용 가능합니다. 구체적인 공정 요구사항 및 제품 적용 사양은 다음과 같습니다.

<table><thead><tr><th width="180">항목</th><th>세부 요구사항</th><th>사양</th></tr></thead><tbody><tr><td><strong>소재 적용</strong></td><td>핵심 사양</td><td>40 kHz (800 W)</td></tr><tr><td><strong>음극 용접</strong></td><td>소재 재질 / 두께</td><td>Copper Foil / 4~8 μm</td></tr><tr><td></td><td>탭(Tab) 재질 / 두께</td><td>Nickel Tap / 0.06~0.1 mm</td></tr><tr><td><strong>양극 용접</strong></td><td>소재 재질 / 두께</td><td>Al Foil / 6~25 μm</td></tr><tr><td></td><td>탭(Tab) 재질 / 두께</td><td>알루미늄(Al) / 0.06~0.1 mm</td></tr><tr><td><strong>배터리 셀 적용</strong></td><td>셀 구조 / 적층 수</td><td>권취형(Jelly Roll) 또는 적층형(Stacking) / 1~20층</td></tr><tr><td></td><td>용접 자국 크기</td><td>4 mm × 4 mm (맞춤 제작 가능)</td></tr><tr><td><strong>용접 혼</strong>(Horn) <strong>/ 앤빌</strong>(Anvil)</td><td>용접 혼 재질 / 수명</td><td>수입산 고속도강(HSS) / 음극 30만 회 이상, 양극 50만 회 이상</td></tr><tr><td></td><td>앤빌 재질 / 수명</td><td>고속도강(HSS) / 음극 30만 회 이상, 양극 50만 회 이상</td></tr></tbody></table>

## 2. 안전 및 주의사항

### 2-1. 경고 표지 및 기호 설명

{% hint style="danger" %}
**위험 (DANGER)** — 지시사항을 준수하지 않을 경우 사망 또는 중상으로 이어질 수 있는 즉각적인 위험 상황을 의미합니다.
{% endhint %}

{% hint style="warning" %}
**경고 (WARNING)** — 지시사항을 준수하지 않을 경우 사망 또는 중상으로 이어질 수 있는 잠재적인 위험 상황을 의미합니다.
{% endhint %}

{% hint style="info" %}
**주의 (CAUTION)** — 지시사항을 준수하지 않을 경우 경상 또는 장비 손상이 발생할 수 있는 위험 상황을 의미합니다.
{% endhint %}

### 2-2. 작업자 안전 수칙

**안전 주의사항 (Safety Precautions)**

장비 설치 및 사용 전 본 사용설명서를 충분히 숙지해 주시기 바랍니다.\
본 장비는 작업자의 안전을 고려하여 설계되었으나, 부주의하거나 올바르지 않은 사용으로 인해 안전사고 또는 장비 손상이 발생할 수 있습니다.\
안전한 장비 사용과 장비 보호를 위해 사용 전 아래의 안전 주의사항 및 사용방법을 반드시 확인해 주시기 바랍니다.

{% hint style="danger" %}
장비 및 전기 제어함 내부에는 고전압이 인가되는 부분이 있으니커버 분리 또는 유지보수 작업 전에는 반드시 전원을 차단해야 합니다.
{% endhint %}

* 장비 내부에는 고전압이 흐르는 부분이 있습니다. 커버를 분리하거나 유지보수 작업을 진행하기 전에는 반드시 전원을 차단해야 합니다.
* 장비는 3핀 전원 플러그를 사용하며 올바르게 접지된 상태에서 사용해야 합니다.
* 장비는 반드시 정상적으로 접지된 전원 콘센트에 연결해야 합니다.
* 전기 제어함 내부에는 고전압이 인가되는 부분이 있으므로 작업 시 각별한 주의가 필요합니다.
* 초음파 트랜스듀서(진동자)의 전기 접점은 직접 접촉해서는 안 됩니다.
* 초음파 출력 중에는 용접 혼(Horn) 또는 부스터(Booster)를 손으로 잡거나 접촉해서는 안 됩니다.
* 승인 없이 용접 혼의 구성이나 구조를 임의로 변경해서는 안 됩니다.
* 40 kHz 초음파 용접 작업 시 정상 작동 상태에서도 초음파 작동음이 발생할 수 있습니다.
* 용접 혼에는 별도의 장치나 부속품을 임의로 설치해서는 안 됩니다.

**전기 관련 주의**

{% hint style="danger" %}
솔레노이드 밸브 및 팬 연결 포트에는 AC 220V 전원이 공급됩니다. 설치 또는 점검 작업 전에는 반드시 전원을 차단해야 합니다.\
_(1-2. 본체 후면 참조)_
{% endhint %}

{% hint style="warning" %}
냉각 팬은 AC 220V 전원을 사용하므로 설치 및 점검 시 주의가 필요합니다.\
_(1-2. 용접 헤드 참조)_
{% endhint %}

### 2-3. 설치 환경 주의사항

* 장치가 구동 시 흔들림이 없어야 하므로 평평한 테이블 위에 설치합니다.
* 장치 셋팅 시 및 유지보수를 위해 장치 주변 최소 50cm 이상의 여유 공간이 필요합니다.

## 3. 설치 및 운반

### 3-1. 운반 및 이동

* 장치 이동 시 디스플레이와 헤드를 연결하고 있는 선들을 분리하여 이동하는 것을 권장드립니다.

### 3-2. 유틸리티 연결

<table><thead><tr><th width="161">유틸리티</th><th>내용 (본문 기준)</th></tr></thead><tbody><tr><td>전원</td><td>AC 220V / 50Hz — 전원 케이블 포트(본체 뒤면)에 연결</td></tr><tr><td>압축 공기</td><td>M8 에어 호스 권장, 압력 조절 밸브로 2~3kg/cm² 조절</td></tr><tr><td>풋 스위치</td><td>풋 스위치 포트(본체 뒤면) — 자동 공급 장치의 트리거 신호 입력 겸용</td></tr></tbody></table>

{% hint style="info" %}
상세 연결 순서는 **4-2. 장비 조작**의 작동 절차(1\~3단계)를 참조하세요.
{% endhint %}

## 4. 사용 및 조작 방법

### 4-1. 사용 전 준비사항

**용접 헤드 설치 시 주의사항**

1. 진동자와 용접 혼(Horn)의 접촉면은 깨끗하고 평탄한 상태를 유지해야 하며, 균열이나 손상이 없어야 합니다.
2. 부스터(Booster)와 용접 혼은 휘어짐이나 변형이 없는 상태여야 합니다.
3. 용접 혼 조립부를 설치하거나 분리할 때는 반드시 지정된 전용 공구를 사용해야 합니다.
4. 모든 나사 체결부가 단단히 고정되어 있고, 각 접촉면의 접촉 상태가 양호한지 확인해야 합니다.
5. 전원을 켠 후 무부하 상태에서 Sonic Test(초음파 테스트) 버튼을 눌러 작동 상태를 확인합니다. 테스트 시 약한 고주파음이 발생하며, 부스터에서 미세한 진동이 느껴질 수 있습니다.

{% hint style="warning" %}
**경고:** 초음파 테스트 중에는 부스터를 손으로 잡거나 강하게 접촉해서는 안 됩니다. 초음파 진동으로 인해 피부 화상이 발생할 수 있습니다.
{% endhint %}

**용접 헤드 정렬**

용접 혼을 지그에 장착한 후 실린더를 수동으로 작동하여 혼이 하부 금형에 닿을 때까지 천천히 하강시킵니다. 정렬 상태를 확인한 후 지그를 단단히 고정합니다. 용접 위치에서 용접 혼과 하부 금형이 서로 평행하고 정확하게 정렬되어 있는지 확인해야 합니다.

### 4-2. 장비 조작

**작동 절차**

{% stepper %}
{% step %}
### 초음파 및 풋스위치 연결

도면 1의 초음파 발진기(Ultrasonic Generator)와 도면 2의 용접 혼(Horn)을 연결하고, 풋스위치를 연결합니다.
{% endstep %}

{% step %}
### 전원 연결

도면 3과 같이 전원 케이블을 본체에 연결합니다.

{% hint style="warning" %}
⚠ 별도 표기가 없는 경우 본 장비는 AC 220V / 50Hz 전원을 사용합니다.
{% endhint %}
{% endstep %}

{% step %}
### 에어 연결

도면 2의 ③번 에어 레귤레이터(Air Regulator)에 에어 호스를 연결하여 압축공기를 공급합니다.

※ 에어 호스는 M8 규격 사용을 권장합니다.
{% endstep %}

{% step %}
### 혼 위치 조정

용접 대상물에 맞게 혼(Horn)의 위치를 조정합니다. 용접 시 혼과 하부 금형의 접촉면이 평행하게 맞도록 정렬 상태를 확인합니다.
{% endstep %}

{% step %}
### 전원 스위치 ON

본체의 전원 스위치를 ON으로 전환합니다.
{% endstep %}

{% step %}
### 초음파 테스트

도면 1의 ⑤번 Freq Scanning(주파수 스캔) 버튼을 눌러 발진기, 진동자(Transducer) 및 혼(Horn)의 주파수를 자동으로 매칭합니다.

이후 도면 1의 ⑮번 Sonic Test(초음파 테스트) 버튼을 눌러 초음파 출력 및 주파수 매칭 상태가 정상인지 확인합니다.

{% hint style="info" %}
제조사 제공 기준으로 주파수가 정상적으로 매칭된 경우 전류는 약 0.3 A, 주파수는 약 40 kHz로 표시됩니다.
{% endhint %}
{% endstep %}

{% step %}
### 공압 조절

공압은 **2\~3kg/cm²** 로 조절합니다. 에어 레귤레이터를 사용하여 공급 공압을 조정합니다.
{% endstep %}

{% step %}
### 혼 높이 및 스트로크 조정

도면 2의 ①번 에어 실린더를 통해 혼의 하강 스트로크를 조정하고, ⑧번 상승 스트로크 조절 나사를 통해 혼의 상승 스트로크를 조정합니다.
{% endstep %}

{% step %}
### 진폭 및 출력 조정

조작 화면의 Amplitude(진폭)를 설정하여 용접 대상물에 맞게 초음파 출력 세기를 조정합니다.

※ 장비 검수 및 테스트 용접 시 Amplitude 50%를 참고값으로 사용합니다. 실제 설정값은 용접 소재 및 용접 상태에 따라 조정합니다.
{% endstep %}

{% step %}
### 시간 조절

도조작 화면의 ⑮\~⑲번 항목을 사용하여 용접 조건을 설정합니다.

{% hint style="warning" %}
⚠ 용접 품질은 진폭, 용접 에너지 또는 용접 시간 등 설정 조건에 따라 달라질 수 있으므로 실제 용접 상태를 확인하면서 단계적으로 조정합니다.
{% endhint %}
{% endstep %}
{% endstepper %}

### 4-3. 사용 후 정리

_(원본 문서에 해당 내용 없음 — 추후 작성)_

## 5. 유지보수 및 트러블슈팅

### 5-1. 정기 점검 항목

_(원본 문서에 해당 내용 없음 — 추후 작성)_

### 5-2. 주요 소모품 및 부품 교체

| 부품 명칭     | 비고 (본문 기준)                                           |
| --------- | ---------------------------------------------------- |
| 퓨즈 (15A)  | 과전류·과부하 시 회로 차단 — 단선 시 교체                            |
| 용접 헤드 (혼) | 교체 시 고정 나사 사용, 교체 후 **Freq Scanning** 버튼으로 주파수 보정 필요 |

### 5-3. 트러블슈팅

**과부하 보호**

장비에 과부하가 발생하면 발진기에서 경고음이 발생하며, 과부하 보호 회로가 작동하여 초음파 출력을 중단합니다.

설정이 적절하지 않거나 용접부 조립 상태가 느슨한 상태에서 장비를 작동할 경우 과부하가 발생할 수 있으며, 과부하 보호 기능은 전원부 및 주요 구성품을 보호하기 위해 작동합니다.

과부하 상태가 발생하면 과부하 표시등이 계속 점등됩니다. 과부하가 반복적으로 발생하는 경우 장비 고장을 방지하기 위해 원인을 확인하고 문제를 해결해야 합니다.

**과부하 발생 시 점검 사항**

* 진동자(Transducer)의 이상 여부를 확인합니다.
* 부스터(Booster)의 이상 여부를 확인합니다.
* 혼(Horn)의 하강 속도를 확인합니다.
* 연결 스터드의 체결 상태를 확인합니다.
* 진동자와 혼의 접촉면 상태를 확인합니다.
* 진동자, 혼 및 부스터에 균열이 있는지 확인합니다.
* 용접 중 표시되는 에너지 비율이 100%를 초과하는지 확인합니다. 100%를 초과하는 경우 더 높은 출력의 발진기가 필요할 수 있습니다.
* 위 항목을 확인한 후에도 원인을 찾을 수 없는 경우 제조사 A/S에 문의해야 합니다.

**고장 및 유지보수**

| 이상 현상                          | 원인                                                       | 조치 방법                                                       |
| ------------------------------ | -------------------------------------------------------- | ----------------------------------------------------------- |
| 초음파 발생기 전원을 켰으나 전원 표시등이 켜지지 않음 | <p>① 전원 스위치 접촉 불량  </p><p>② 전원 퓨즈 단선</p>                 | <p>① 전원 스위치를 여러 번 눌러 작동 여부 확인 또는 교체 </p><p>② 퓨즈 확인 후 교체</p> |
| 용착 불량                          | <p>① 출력 전력이 너무 낮음 </p><p>② 용착 시간이 너무 짧거나 김</p>           | <p>① 출력 전력을 높여 재설정 </p><p>② 용착 시간을 적절히 조정하여 재설정</p>         |
| 전원 인가 시 퓨즈 단선                  | <p>① 파워 트랜지스터(출력 소자) 손상 </p><p>② 브리지 정류기(다이오드 모듈) 손상</p> | <p>① 파워 트랜지스터 교체 </p><p>② 브리지 정류기 교체</p>                    |
| 전원 ON 후 용접 시 출력 없음             | 풋 스위치 고장                                                 | 풋 스위치 교체                                                    |

{% hint style="info" %}
기타 원인은 공급사에 문의하십시오. (→ **6. 기술지원**)
{% endhint %}

## 6. 기술지원 (A/S)

### 6-1. A/S 접수 절차 및 문의처

{% stepper %}
{% step %}
### 장비 정보 확인

장비 모델명(SP-DH1000)과 **시리얼 번호**를 확인합니다.
{% endstep %}

{% step %}
### 1차 확인

**5-3. 트러블슈팅**과 대조하여 1차 확인합니다.
{% endstep %}

{% step %}
### 문의

해결되지 않는 경우 아래 문의처로 연락합니다. 이상 현상 사진/영상을 함께 보내 주시면 처리가 빠릅니다.
{% endstep %}
{% endstepper %}

| 구분 | 내용 |
| -- | -- |
|    |    |
|    |    |
|    |    |

### 6-2. 품질 보증 기간 및 조건

| 구분         | 기간    |
| ---------- | ----- |
| 본체         |       |
| 소모품 (퓨즈 등) | 보증 제외 |
