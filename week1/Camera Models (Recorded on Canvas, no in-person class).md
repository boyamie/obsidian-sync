

---

### Lecture 2: Camera Models
이 강의는 **카메라 모델**에 대해 다루고 있다.
(핀홀 카메라, 렌즈와 카메라의 기하학적 관계 등)

### 주요 내용
1. **Pinhole Cameras**:![[스크린샷 2024-08-26 오후 3.04.30.png]]
   - 핀홀 카메라의 기본 원리와 구성
   - **Aperture**(조리개)의 역할과 중요성
   - 핀홀 카메라를 사용하여 이미지가 어떻게 형성되는지 논의

2. **Camera History**:
   - **Leonardo da Vinci**(레오나르도 다 빈치)가 최초로 기록한 **Camera Obscura**(카메라 옵스큐라) 개념을 소개
   - **Johann Zahn**(요한 자흔)과 **Joseph Nicéphore Niépce**(조제프 니세포르 니엡스)가 최초의 휴대용 카메라 및 사진을 개발한 과정
   - 사진의 발전과정, **Daguerréotypes**(다게레오타입) 및 **Color Photography**(컬러 사진)의 출현

3. **Pinhole Perspective Projection**:
   - 핀홀 카메라의 투영 방정식을 소개하며, 이 방정식을 사용하여 3D 공간에서 2D 평면으로의 변환
   - 기하학적 변환을 통해 어떻게 이미지를 계산할 수 있는지

4. **Cameras & Lenses**:
   - 렌즈의 역할과 **Focal Length**(초점 거리)에 대해 설명
   - 렌즈를 통해 빛이 필름에 어떻게 초점이 맞춰지는지 설명하고, **Depth of Field**(심도) 개념

5. **Lens Distortion**:
   - 렌즈의 왜곡 문제를 설명하며, 특히 **Radial Distortion**(방사 왜곡)
   - **Barrel Distortion**(배럴 왜곡)과 **Pincushion Distortion**(핀쿠션 왜곡)과 같은 렌즈 왜곡의 예를 설명

6. **Intrinsic and Extrinsic Parameters**:
   - **Intrinsic Parameters**(내부 파라미터)와 **Extrinsic Parameters**(외부 파라미터)의 개념을 소개하고, 카메라 모델에서 이들이 어떻게 사용되는지 설명
   - **Camera Matrix**(카메라 매트릭스)의 구성과 역할

7. **3D Transformations**:
   - 3D 공간에서의 **Translation**(이동), **Scaling**(스케일링), **Rotation**(회전) 변환을 다루며, 이들이 카메라 모델에서 어떻게 사용되는지 설명
   - **Homogeneous Coordinates**(동차 좌표)를 사용하여 이러한 변환을 표현하는 방법

8. **Projective Transformations**:
   - **Projective Transformation**(사영 변환)의 개념을 소개하고, 이 변환이 이미지에서 어떻게 적용되는지
   - 평행선이 이미지에서 **Vanishing Point**(소실점)에서 어떻게 만나게 되는지

### 다음 강의 예고
**Camera Calibration**(카메라 보정) 방법

---

이 강의는 **카메라 모델**에 대한 깊이 있는 이해를 제공하며, 특히 3D 공간에서의 투영과 변환을 중점적으로 다룹니다. 강의에서 다룬 내용을 더욱 깊이 이해하기 위해 관련 수식을 공부하거나 추가 자료를 참고하는 것도 좋습니다.

추가적인 설명이 필요하거나 특정 부분에 대해 더 알고 싶으시면 언제든지 질문해 주세요!