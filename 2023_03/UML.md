# UML
>- Unified Modeling Language 의 약자 (통합 모델링 언어)  
>- 프로그래밍 언어가 아닌 실제 개발 단계에 들어가기 전, 계획을 디자인 및 시각화하는 것이다. (기호와 도식 사용)  
>- 객체지향 소프트웨어를 개발할 때 시스템과 산출물을 **명세화, 시각화, 문서화** 할 때 사용한다.

<br>

UML에 따라 작성한 문서는 표준 양식에 의해 작성된 문서이기 때문에, 이해하기 편하며 효율적으로 의사소통 할 수 있다. 복잡한 시스템을 시각적으로 모델링하여 구조를 보다 알아보기 쉽다.  

<br>

## 목차
- [UML 종류](#UML-종류)
- [UML 방법](#UML-방법)
- [자주 사용하는 다이어그램 2가지](#자주-사용하는-다이어그램-2가지)
- [UML 이용 모델링](#UML-이용-모델링)

<br>

## UML 종류
1. 구조 다이어그램 (Structure Diagram)
    - 클래스 다이어그램 (Class Diagram)  
        클래스의 속성, 메서드, 관계를 표현  
    - 객체 다이어그램 (Object Diagram)  

    - 배치 다이어그램 (Deployment Diagram)  
        프로그램의 아키텍처를 물리적인 관점에서 설계
    - 컴포넌트 다이어그램 (Component Diagram)  
        소프트웨어 컴포넌트들과 그들의 관계, 구조를 표현
    - 패키지 다이어그램 (Package Diagram)  
        관련있는 요소들을 하나의 패키지로 묶고, 패키지 사이의 관계를 표현
    - 복합 구조 다이어그램 (Composite Structure Diagram)  

    - 프로필 다이어그램 (Profile Diagram)  


<br>

2. 행위 다이어그램 (Behavior Diagram)
    - 시퀀스 다이어그램 (Sequence Diagram)  
        객체간의 상호작용을 시간의 흐름에 따라 나타낸다.
    - 유스케이스 다이어그램 (UseCase Diagram)  
        사용자(Actor)의 관점에서 시스템의 기능, 상호작용과 그들간의 관계를 표현  
    - 활동 다이어그램 (Activity Diagram)  
        프로그램의 시작과 끝을 정의하고, 작업의 수행과정을 단계적으로 정의
    - 커뮤니케이션 다이어그램 (Communication Diagram)  
        객체간의 상호작용을 메시지의 관점으로 나타낸다
    - 상태 다이어그램 (Sate Diagram)  
        객체가 취할 수 있는 상태와 상태변화를 표현
    - 타이밍 다이어그램 (Timing Diagram)  

    - 상호작용 개요 다이어그램 (Interaction Overview Diagram)  


<br>

## UML 방법
UML의 방법은 크게 3가지이다.

1. **OOA** : Object Oriented Analysis (객체지향 분석)  
    서비스가 무엇을 작업해야하는지
2. **OOD** : Object Oriented Design (객체지향 디자인)  
    어떻게 이러한 작업이 수행되는지
3. **OOP** : Object Oriented Programing (객체지향 프로그래밍)  
    이러한  모든 것을 구현하는지

<br>

## 자주 사용하는 다이어그램 2가지

1. [Sequence Diagram (시퀀스 다이어그램)](https://github.com/yeonledev/TIL/blob/main/2023_03/UML/sequenceDiagram.md)
2. [Class Diagram (클래스 다이어그램)](https://github.com/yeonledev/TIL/blob/main/2023_03/UML/classDiagram.md)  

<br>

## UML 이용 모델링
- 기능 모델링  
    시스템이 제공할 기능 표현, 사용자 관점

    - 유스케이스 다이어그램  
        사용자의 요구를 분석하여 기능을 모델링하는 작업에 사용
    - 활동 다이어그램  
        객체의 프로세스나 로직의 처리 흐름을 순서에 따라 표현

<br>

- 정적 모델링  
    시스템 내부 구성 요소 표현, 개발자 관점

    - 클래스 다이어그램  
        클래스와 클래스 사이의 관계 표현, 시스템의 구조와 문제점 파악 가능
    - 패키지 다이어그램  
        모델 요소들을 그룹화한 패키지들의 관계 표현

<br>

- 동적 모델링  
    시간의 흐름에 따라 변화(동작)하는 과정, 상호작용 표현

    - 상태 다이어그램  
        상태 변화를 표현
    - 시퀀스 다이어그램  
        시스템과 객체들이 주고받는 메시지 표현, Lifeline, 실행, 메시지, 상호작용 등으로 구성

