# Setting Eclipse

> ## 1. 메모리 설정
>   
> 경로 : C:\eGovFrameDev-3.8.0-64bit\eclipse\eclipse.ini
> 변경 내용
>
> -Xms512m  >>  -Xms1024m  
> -Xmx1024m >>  -Xmx1024m
*****
> ## 2. 인코딩 UTF-8 설정
> 경로 : Window > Preferences > 'encoding' 검색  
> 전체 UTF-8로 설정
*****
> ## 3. Code default Template 설정 ([shift] + [alt] + [J])
> 경로 : Window > Preferences > 'template' 검색 > Java > Code Style > Code Template > Comments > Types, Methods  
>
> Types 설정
> ```
>/**
> * @since  : ${date}
> * @author : ${user}
> * <PRE>
> * -----------------------------
> * 개정이력
> * ${date} ${user} : 최초작성
> * </PRE> 
> */
> ```
> Methods 설정
> ```
>/**
> * @Author : ${user}
> * @Date   : ${date}
> * @method : ${enclosing_method} 
> * @return : ${return_type} 
> */
> ```
*****

> ## 4. 자동완성 설정
> 경로 : Window > Preferences > 'template' 검색 > Java > Code Style > Editor > Template > New  
>
> Test Code 용 주석 설정
>
> ```
> name : gwr
> Description : TestCodeCreate
> Pattern : 
>
>	//given
>
>
>	//work
>
>
>	//result
> ```
> 현재 날짜 자동 완성 설정
>
> ```
> name : cd
> Description : 현재 날짜
> Pattern :  ${date}
> ```
*****

> ## 5. Tasks 설정 ( //TODO  : )
> 경로 : Window > Preferences > 'task tag' 검색 > Java > Compiler > Task Tags
> 
*****

> ## 6. Eclipse 설정 Export
> 경로 : File > Export > General > Preferences   
> Export all 체크, 이클립스 설정.epf >> Export finish


