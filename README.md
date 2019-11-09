# 2019-2 객체지향 프로그래밍 프로젝트 - **BOX HEAD - The Goblin**
구성원: 2-3 김진욱 | 2-6 박정민

## 1. 주제
학교로 들어오는 악령을 마법으로 막는다.
TPS

## 2. 동기
현재 만들려 하는 게임의 모티브인 Boxhead 는 좀비물이다. 총기류에 익숙하지 않기에 Boxhead의 아이템으로 나오는 총기들의 특성을 이해하기 어려워 총기가 아닌 조금 더 친숙한 판타지적 요소, 마법을 공격으로 사용하는 게임을 만들어보고 싶었다.
수업을 듣거나 자습을 하다보면 ‘자고싶다’, ‘게임하고싶다’등의 유혹이 든다. 이러한 유혹이 사실 악령에 의한 것이 였다면 어떨까 생각하였다. 그러한 악령들로부터 우리 학생들을 수호하여 쾌적한 학습환경을 만들어주는 수호자가 존재하면 좋겠다는 생각에 그러한 설정을 가진 주인공을 만들어, 세종과학예술학교 건물을 배경으로 악령을 퇴치하는 게임을 만들게 되었다.

## 3. 프로그램 사용 대상
학교를 수호하고 있다는 사명감을 가지고 스트래스를 해소하고 싶어하는 SASA의 학생들

## 4. 목적
교칙에 어기지 않고 학생이 스트래스를 적절히 해소할 수 있는 5~10분 동안 플레이 할 수 있는 짧은 텀의 게임을 만든다.
총기가 아닌 마법류의 공격을 하는 만큼, 공격에 의한 디버프 효과에 집중한 게임을 만든다.

## 5. 주요기능
1. 스프라이트를 이용한 화려한 애니메이션
1. 악령  
	1. 종류  
		1. 하급
		1. 상급
	1. 정보
    	1. hp
    	1. 공격력
    	1. 이동속도
1. 여러 종류의 마법 공격
  	1. 종류
    	1. fireball
    	1. blade
    	1. leaf
    	1. dark
    	1. lightning
  	1. 정보
    	1. 공격력
    	1. 소비mp
    	1. 이동속도
1. hp / mp 시스템  
    hp는 체력으로, 악령과 접촉할시 깎여나간다.  
    mp는 스킬을 사용할 때 필요한 에너지로, 매초 일정량 회복된다. 최대치가 존재한다.
2. 학교를 배경으로 한 스테이지  
    hp 가 0이 될 때까지 진행

## 6. 프로젝트 핵심
sprite 를 이용한 화려한 움직임과 스킬

## 7. 구현에 필요한 라이브러리나 기술
pygame
스프라이트

## 8. **분업 계획**
김진욱 : 마법 공격, 점수판 프로그래밍
박정민 : 스프라이트를 이용한 캐릭터 이동. 맵 제작. 몹스폰. 몹AI

## 9. 기타

<hr>



https://repl.it/@james1990a/UnselfishJoyfulDecimals
