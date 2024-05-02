# 수면 건강과 생활 습관 간의 연관성 분석
keggle에 존재하는 수면 건강과 생활 습관에 대한 데이터를 통해 다양한 생활 습관이 수면의 질에 미치는 영향을 분석하고자 합니다. 
특정 생활 습관 패턴이 좋은 수면을 촉진하거나 방해하는 요소를 파악하여 보다 건강한 생활을 위한 가이드라인을 제안하는 것이 목표입니다.
## 데이터 설명 및 분석 목적
- Person ID: 각 참가자의 고유 식별자
- Gender, Age, Occupation: 참가자의 성별, 나이, 직업
- Sleep Duration: 하루 평균 수면 시간
- Quality of Sleep: 수면의 질을 1에서 10까지(최악의 경우가 1) 평가
- Physical Activity Level: 하루에 신체 활동에 사용하는 시간(minutes/day)
- Stress Level: 개인이 경험하는 주관적인 stress level을 1에서 10까지(최악의 경우가 10) 평가
- BMI Category: Underweight, Normal, Overweight로 BMI에 따라 분류
- Blood Pressure (systolic/diastolic): 개인의 혈압(최고 혈압/최저 혈압)
- Heart Rate (bpm): 개인의 심장 박동을 bpm으로 표현
- Daily Steps: 개인의 일일 걸음수
- Sleep Disorder: 수면 장애의 유무(None, Insomnia, Sleep Apnea)

분석 목적
- 이 데이터를 통해, 수면의 질과 수면 시간에 영향을 미치는 주요 요인들을 파악합니다.
- 수면 장애 유무에 관련된 주요 요인들을 파악하여, 이를 기반으로 예방 및 생활 패턴 개선 방안을 모색합니다.

## 분석 과정
1. Descriptive Statistics: Numeric data(Age, Sleep duration, Quality of Sleep, Physical Activity Lvel, Stress Level, Blood Pressure, Heart Rate, Daily Steps)에 대해 Average, Variation을 각각 구합니다.
2. Correlation Analysis: Multiple Linear regression을 통해 predictors 간의 correlation을 분석하여 수면에 영향을 미치는 요인을 파악하고, 영향도를 분석합니다.
3. Group Comparisons: BMI category, Sleep Disorder에 따라 Quality of Sleep을 구분합니다.
4. Visual Analysis: 2번의 결과에 따라 significant 한 relationship을 plot으로 나타냅니다. 그리고 3번의 결과에 따라 KNN을 통해 visualize 합니다.
5. Recommendation: 위의 분석을 통해 수면의 질을 올릴 수 있는 guideline을 제시합니다.
6. Predictive model: 2번의 결과에 따라 
