# KSAFM_Data_FloX
저널: 한국농림기상학회
논문타입: Data

# Sun-induced Fluorescence
대한민국 나주시 산포면 전남농업기술원 논 포장에서 FloX 광학 관측 기기에서 관측된 자료를 이용하여 산출한 SIF 자료이다.

위경도: 위도: 35.0275°, 경도: 126.8209°  
작물: 논벼  
관측기기: FloX  
관측기간: 2010.06.10.~2010.10.05.  
SIF 산출 프로그램 버전: 14.2. (R 프로그래밍 기반 GUI)
필터링이 수행된 데이터 버전: 1.0.

# Author
주저자: Jae-Hyun Ryu, Department of Applied Plant Science, Chonnam National University (ryu.jaehyun88@gmail.com)   
교신저자: Jaeil Cho, Department of Applied Plant Science, Chonnam National University (chojaeil@gmail.com)  
공동저자: Seon Woong Jang, Hyunki Kim, Hyun-Dong Moon, Seo-Ho Sin, Yang-Won Lee  

# Raw Data Source
Last access @ December 1, 2020
기후작물생리학실험실, 응용식물학과, 전남대학교 (Prof. Cho)

# Data processing
1. FloX에서 관측된 자료를 R기반 GUI 프로그램을 이용하여 iFLD, SFM 방법으로 SIF 산출
2. 태양천정각(Solar Zenith Angle)을 이용한 데이터 필터링
3. Saturation 상태를 고려한 데이터 필터링
4. 1회 관측시 급격한 광이 변한 경우 필터링
5. Sun glint 영향 최소화
6. SIF 값이 0.0 미만인 경우 필터링

# Note
낮음 품질의 자료를 제거하기 위해 필터링을 수행하였만 제공된 SIF 자료는 관측 오차를 포함하고 있음
제공된 자료를 학술적으로 사용하는 경우 출판된 농림기상학회 논문을 참조하여야 함
제공된 자료를 상업적으로 사용하기 위해서는 저자의 동의를 얻어야 함
