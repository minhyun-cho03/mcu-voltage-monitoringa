# mcu-voltage-monitoringa
# MCU Voltage Monitoring (Beginner Firmware Project)

## 목적
펌웨어 직무를 준비하면서, MCU가 실제 전압(아날로그)을 ADC로 읽고,
그 값을 기준으로 판단/출력하는 흐름을 기초부터 이해하기 위한 프로젝트.

## 최종 목표
- 전압을 ADC로 읽는다
- ADC 값을 실제 전압으로 계산한다
- 임계값을 넘으면 상태(정상/위험)를 판단한다
- LED 또는 Serial로 상태를 표시한다

## 진행 방식 (단계별)
1. ADC 값 읽기 (포텐셔미터)
2. ADC → 전압 환산
3. 임계값 비교 + LED 출력
4. 노이즈 대응(히스테리시스/평균)

## 사용 예정
- Arduino UNO (입문용)
- (추후) STM32로 확장 예정
