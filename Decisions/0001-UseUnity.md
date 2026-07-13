# ADR-0001: Unity 2D와 C# 사용

- 상태: `approved`
- 날짜: 2026-07-13

## 배경

원래 계획서는 HTML, CSS, JavaScript 기반 웹게임을 제안했으나 사용자는 Unity 제작을 희망한다.

## 결정안

Unity의 2D 물리, Collider2D, Prefab, Tilemap과 C#을 사용한다. 결과물은 Windows PC 실행 파일로 제작하며 WebGL과 모바일 빌드는 범위에서 제외한다.

## 영향

- 이동, 충돌, 투사체, 타일맵과 애니메이션을 Unity 편집기에서 구성할 수 있다.
- C#과 Unity 컴포넌트 구조를 학습해야 하므로 초기 난이도가 증가한다.
- 계획서의 기술 항목과 결과물 표현을 Unity 및 Windows 실행 파일 기준으로 수정해야 한다.
- 구현 저장소는 설계 저장소와 분리한다.

## 승인 조건

사용자가 2026-07-13에 Unity와 Windows 단일 플랫폼을 명시적으로 선택했다.
