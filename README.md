# 다향성 콘솔 몬스터 게임
> 해당 라운드의 몬스터를 다 처치하면 다음 라운드로 넘어가는 게임

<br>

## [플레이어]와 [몬스터] 공동 필드
- name  :  이름
- maxHp : 최대 체력
- curHp : 현재 체력
- isFaint : 기절 여부

<br>

## 공격 순서
플레이어 1명 공격 -> 몬스터 전체 공격 -> 플레이어 1명 공격 -> 몬스터 전체 공격 -> 플레이어 1명 공격 -> . . . 

<br>

## [플레이어] 설명
#### HP : 500~1000 사이 랜덤
#### POWER : 50 ~ 95 사이 랜덤
<br>

* ### 전사 Warrior
  * 스킬 - 모든 적을 공격한다

* ### 마녀 Witch
  * 스킬 - 모든 적을 한 턴 기절 시킨다 

* ### 힐러 Hiller
  * 스킬 -  모든 아군의 체력을 30HP 회복시킨다

<br>

## [몬스터] 설명 
#### 몬스터는 랜덤 hp 랜덤 파워
#### 각 라운드마다 4마리씩 출현한다
#### 20분의 1의 확률로 스킬 발동
<br>

* ### 오크 Orc
  * 스킬 - 적을 2배의 파워로 공격 + 기절 시킨다

* ### 늑대 Wolf
  * 스킬 - 적 전체를 공격력의 절반 데미지로 공격한다

* ### 박쥐 Bat
  * 스킬 - 적 1명을 기절시킨다



---

## Class Diagram(UML)

<img src="image/Game.jpg">

---

## Demo

![Demo.gif]()

