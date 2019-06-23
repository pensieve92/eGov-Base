# Setting Eclipse

> ## 1. 메모리 설정
>   
> 경로 : C:\eGovFrameDev-3.8.0-64bit\eclipse\eclipse.ini
> 변경 내용
>
> -Xms512m  >>  -Xms1024m  
> -Xmx1024m >>  -Xmx1024m

> ## 2. 인코딩 UTF-8 설정
> 경로 : Window > Preferences > 'encoding' 검색  
> 전체 UTF-8로 설정

> ## 3. Code default Template ([shift] + [alt] + [J])
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
> *****
> Methods 설정
> ```
>/**
> * @Author : ${user}
> * @Date   : ${date}
> * @method : ${enclosing_method} 
> * @return : ${return_type} 
> */
> ```
