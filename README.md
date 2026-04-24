# Diversity Train Set 다양성 가상열차세트 /DTS Virtuel
**다양성 가상열차세트**는 <br>
2023년 6월 18일 `Diversity Train Set 다양성 열차세트2 / DTS2`로 등록을 시작했습니다.<br>
당시, 온라인컨텐츠 깃허브의 업로드 오류로 인해 등록되어 방치된 세트였습니다.<br>
2026년 2월 28일 `Diversity Train Set 다양성 열차세트 / DTS`에서 가상열차로만 분리 작업이 진행되어 새로운 여정을 시작하게 되었스니다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS_Virtual/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
[1.02] <br>
* [버그] KTX-청룡 DD 잘못된 구매창 이미지 수정 ([#3](https://github.com/DTS-NewGRF/DTS_Virtual/issues/3))(2026.04.24)
* [버그] Glory 430 16량 중량계산 실수 ([#23](https://github.com/DTS-NewGRF/DTS_Virtual/issues/23))(2026.04.24)

## 인게임 등록
[1.01] <br>
* [열차변경][도색추가] KTX-청룡 DD 2세대 ([#4](https://github.com/DTS-NewGRF/DTS_Virtual/issues/4))(2026.03.22)
* [열차변경] 가상차량 성능 조정 ([#5](https://github.com/DTS-NewGRF/DTS_Virtual/issues/5))(2026.03.23)
* [열차변경] DTX-Metro R001 10량 편성 조정 ([#6](https://github.com/DTS-NewGRF/DTS_Virtual/issues/6))(2026.03.24)
* [열차변경] HYEL-15 성능 조정 ([#7](https://github.com/DTS-NewGRF/DTS_Virtual/issues/7))(2026.04.16)
* [열차변경] DFX 성능 조정 ([#8](https://github.com/DTS-NewGRF/DTS_Virtual/issues/8))(2026.04.16)
* [열차변경] DPX 성능 조정 ([#9](https://github.com/DTS-NewGRF/DTS_Virtual/issues/9))(2026.04.16)
* [열차변경] PEX-SUPER 우편객차 수송량 조정 ([#10](https://github.com/DTS-NewGRF/DTS_Virtual/issues/10))(2026.04.16)
* [열차변경] DTX-Metro L150 비정상적인 중량 수정 ([#11](https://github.com/DTS-NewGRF/DTS_Virtual/issues/11))(2026.04.16)
* [열차변경] DTX-Metro R001 비정상적인 중량 수정 ([#12](https://github.com/DTS-NewGRF/DTS_Virtual/issues/12))(2026.04.16)
* [열차변경] DTS_CityLink_150 비정상적인 중량 수정 ([#13](https://github.com/DTS-NewGRF/DTS_Virtual/issues/13))(2026.04.16)
* [열차변경] 우진산전 수소연료전지동차 비정상적인 중량 수정 ([#14](https://github.com/DTS-NewGRF/DTS_Virtual/issues/14))(2026.04.16)
* [열차변경] HYEL 기관차 시리즈 비정상적인 중량 수정 ([#15](https://github.com/DTS-NewGRF/DTS_Virtual/issues/15))(2026.04.16)
* [열차변경] 2층객차 비정상적인 중량 수정 ([#16](https://github.com/DTS-NewGRF/DTS_Virtual/issues/16))(2026.04.16)
* [열차변경] HYEL 동차 시리즈 비정상적인 중량 수정 / 일부 열차 수송량 변경 ([#17](https://github.com/DTS-NewGRF/DTS_Virtual/issues/17))(2026.04.16)
* [열차변경] ITX 시리즈 비정상적인 중량 수정 / 성능 변경 ([#18](https://github.com/DTS-NewGRF/DTS_Virtual/issues/18))(2026.04.16)
* [열차변경] KTX 시리즈 비정상적인 수송량 변경 ([#19](https://github.com/DTS-NewGRF/DTS_Virtual/issues/19))(2026.04.16)
* [열차변경] 누리로 DD 비정상적인 수송량, 성능 변경 ([#20](https://github.com/DTS-NewGRF/DTS_Virtual/issues/20))(2026.04.16)
* [열차변경] Glory 430 중량, 수송량 변경 ([#21](https://github.com/DTS-NewGRF/DTS_Virtual/issues/21))(2026.04.17)
* [열차변경] 2층객차(가상 객차 차량) 수송량 조정 ([#22](https://github.com/DTS-NewGRF/DTS_Virtual/issues/22))(2026.04.17)

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.

## 라이선스
DTS_Virtual는 크리에이티브 [커먼스 라이선스 v3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) (CC-BY-NC-SA v3.0)을 따릅니다.<br>
DTS_Virtual 프로젝트에 기여함은 라이선스에 동의함을 의미합니다.