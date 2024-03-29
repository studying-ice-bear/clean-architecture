# 1부 : 소개

## 2장 두 가지 가치에 대한 이야기

### 행위

- 이해관계자를 위해 기계가 수익을 창출하거나 비용을 절약하도록 만들기 위함

### 아키텍처

- 소프트웨어는 '부드러워'야 한다. 즉 변경하기 쉬워야 한다.
- 변경사항을 간단하고 쉽게 적용할 수 있어야 한다.
- 변경사항의 범위와 형태의 차이에 따라 개발 비용의 증가를 결정 짓는다.
- 아키텍처는 형태에 독립적이어야 하고, 그럴수록 더 실용적이다.

### 더 높은 가치

- 수정이 현실적으로 불가능한 시스템은 존재하며, 변경에 드는 비용이 변경으로 창출되는 수익을 초과하는 경우다.
- 소프트웨어의 첫 번째 가치인 행위는 긴급하지만 매번 높은 중요도를 가지는 것은 아니다.
- 소프트웨어의 두 번째 가치인 아키텍처는 중요하지만 즉각적인 긴급성을 필요로 하는 경우는 절대 없다.

**우선순위**

1. 긴급하고 중요한
2. 긴급하지는 않지만 중요한
3. 긴급하지만 중요하지 않은
4. 긴급하지도 중요하지도 않은

아키텍처는 1,2를 차지하지만, 행위는 1, 3에 위치한다.

- 긴급하지만 중요하지 않은 기능과 진짜로 긴급하면서 중요한 기능을 구분할 줄 알아야 한다.

## 결론

아키텍트는 특성과 기능을 개발하기 쉽고, 간편하게 수정할 수 있으며, 확장하기 쉬운 아키텍처를 만들어야 한다.
아키텍처가 후순위가 되면 시스템을 개발하는 비용이 더 많이 들고, 일부 또는 전체 시스템에 변경을 가하는 일이 현실적으로 불가능해진다.
