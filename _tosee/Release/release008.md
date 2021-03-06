---
layout: tosee
title: Version 1.63.0.83
category: Release
order: 8
date : 2019-02-11 12:00:00 +0100
---

## 업데이트 일자 : 2019.02.11
1. FileTrap 기능 추가
   - 랜섬웨어의 차단 및 특정 폴더를 지정하여 폴더내부의 파일들을 랜섬웨어로부터 보호할 수 있는 기능입니다.
   - 탐색기상의 마우스 우클릭시 컨텍스트메뉴추가를 통하여 보호폴더 지정가능.
   - 보호 지정된 폴더의 경우 폴더 아이콘 변경됨.
   - WannaCry , Crypt0L0cker , GandCrab ,GrandCrab ,Satan , petYa 등 총30여가지의 랜섬웨어 테스트
   - 파일 변조로부터 보호 테스트 완료, 추후 MBR 변조에 대해서도 업데이트를 통해 제공할 예정
   - Boot Secure 기능이 있는 경우 파일트랩 설치 제외
   - Microsoft altitude allocation 완료. (마이크로 소프트 파일시스템 및 필터그룹에 등록완료)
   - 기존 Overran Stack 오류 수정
2. CPU, GPU 온도 측정관련 일부 수정
   - 일부 프로세서중 측정이 되지 않는 오류 수정. AMD 프로세서는 추후 지원
3. ToSee Analyzer 에서 이벤트로그 진단 추가
   - 시스템의 오류와 관련된 이벤트만을 수집하여 진단.
   - 추후 업데이트를 통하여 시스템오류 상세진단 추가예정.
4. ToSee Analyzer 리스트뷰의 소트기능 추가.
5. 기타 충돌버그 수정.
6. 테스트OS(Windows7, Windows8.1, Windows10  각각 32/64비트 모두 테스트됨)

### ToSee 매니져사이트 수정
1. 자산관리 및 결과 쿼리 수정 - 동일이름 동일맥어드레스를 가진 자산의 경우
   최신등록된 자산만 표시
2. 상세결과 추가 - 자산별 진단항목의 진단 결과를  O, X 를 통하여 확인할 수
   있도록 수정.
3. 추가 예정 기능 - 자산 개별 진단내역 : 개별 자산에 대한 진단 내역 리스트를
   볼수 있도록 하는 기능.