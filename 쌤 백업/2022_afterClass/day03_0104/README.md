취업의 목적 
웹디자인 : 그래픽 업무 => 상세페이지, 배너, 광고홍보지 ... 
퍼블리싱 : 그래픽 업무 + html, css, javascript => jQuery 
프론트엔드 : javascript => react, veu, angular, svelet ..
        백엔드 단에서 프론트엔드 넘어오는 사람    
그냥 가져다 사용하는 것은 프론트엔드 일( 포토, 일러 )

내가 나의 실력 : 포토샵, 일러 , 코딩


웹페이지 
1. 정보전달 : 어떠한 정보를 전달할까? 
2. 시각을 자극하는 효과 있으면 좋음
3. 사용자 = 타겟
   웹을 사용하는 사용자가 신체건강한 사람만 사용하나? 
   연령대 
   편의성, 사용성, 효율성
   
# 명령체계 시스템 

마우스 제어 :  GUI => 윈도우, 맥, 레드햇
명령어로 제어 : CUI, CLI => 터미널, DOS, 리눅스, 

서버환경 : 리눅스(명령어)

편집툴 : VS CODE(MS) + 라이브러리, 프레임워크, 플러그인, 확장팩 
        아톰, 서브라임, 드림위버 => 브라킷(어도비) => 지원포기


# CUI 사용하여 폴더관리
mkdir
cd
rm
ls
pwd 

## 도스환경에서 파일 목록 확인하기 

```
PS E:\2022_afterClass\day03_0104> dir
```

## 폴더만들기 
```
PS E:\2022_afterClass\day03_0104> mkdir testFolder
```

## 목록확인하기
```
PS E:\2022_afterClass\day03_0104> ls


    디렉터리: E:\2022_afterClass\day03_0104
PS E:\2022_afterClass\day03_0104> ls
                        WriteTime         Length Name
                        ---------         ------ ----
    디렉터리: E:\2022_af오후 2:31     
		           

```

## 폴더 이동 

```
PS E:\2022_afterClass\day03_0104> cd testFolder
Mode                Lasty03_0104\testFolder>WriteTime         Length Name
----                -------------         ------ ----
d-----     2022-01-04
오후 2:31
d-----     2022-01-04   오후 2:31                testFolder
```
## 상위경로로 이동 
```
PS E:\2022_afterClass\day03_0104\testFolder> cd..
PS E:\2022_afterClass\day03_0104> cd..
PS E:\2022_afterClass> cd..
```

## 폴더 지우기 

```
PS E:\> cd 2022_afterClass/day03_0104
PS E:\2022_afterClass\day03_0104> rd day03_0103
rd : 'E:\2022_afterClass\day03_0104\day03_0103' 경로는 존재하지 않으므로 찾을 수 없습
니다.
위치 줄:1 문자:1
+ rd day03_0103
+ ~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (E:\2022_afterClass\day03_0104\day03_0 
   103:String) [Remove-Item], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.RemoveItemC 
   ommand

 ```

## 하위 폴더 지우기

```
PS E:\2022_afterClass\day03_0104> rm  testFolder
PS E:\2022_afterClass\day03_0104> ls
PS E:\2022_afterClass\day03_0104>
```

# 종강까지 만들어야 하는 페이지 
1.  기본사이트(관공서, 공공기관 등)
    서브페이지까지 총 5개 있는 사이트 
2. 반응형 사이트(모바일, 테블릿, 데스크탑, 메가데스크탑)  
3. 기본사이트 소개, 반응형 사이트 소개, 나도 소개   