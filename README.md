# GreenCoffeeBeanDoubleSide

## 학습사용에 용의하도록 디렉토리 이름 영어로 되어있습니다.

|영어|한글|
|----|----|
|Normal|정상두|
|Over-dried|건조|
|Floater|백화두|
|Immature|기형두|
|Shell|조개두|
|Broken|파손|
|Fissure|갈라진두|
|Black|흑|
|Sour|과발효|
|Fungus-damaged|곰팡이두|
|Inspect-damaged|벌레먹은두|
|Foreign matter|이물질|

## 총 2차 데이터 구축 완료
모두 U(위), D(아래)면으로 양면 동시 촬영되었으며, label데이터는 각 디렉토리명.txt로 되어있습니다.

양쪽 촬영 결과에서 한쪽면은 클래스에 해당하지만 다른쪽은 클래스에 해당하지 않는 결점들에 대해서
라벨리을 활용하는 용도로 사용됩니다.

라벨 양식은 아래와 같으며 U-1, U-0, D-1, D-0와 같은 양식으로

U-1(해당 디렉토리 클래스에 해당)

U-0(해당 디렉토리 클래스에 해당되지 않음)

예) 000.png: U-1, D-1, 


### 총: 11,824장

#### 1차 구축
|클래스|수량|
|----|----|
|Black|120|
|Broken|304|
|Fissure|436|
|Fungus-damaged|146|
|Immature|440|
|Inspect-damaged|564|
|Normal|566|
|Over-dried|396|
|Shell|342|
|Sour|158|


#### 2차 구축
|클래스|수량|
|----|----|
|Black|136|
|Broken|1314|
|Fissure|710|
|Floater|128|
|Foreign matter|6|
|Fungus-damaged|986|
|Immature|802|
|Inspect-damaged|1142|
|Normal|1724|
|Over-dried|406|
|Shell|686|
|Sour|312|