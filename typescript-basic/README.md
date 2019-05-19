#  Compiler Options
        
*  compileOnSave
    * true / false (default false)
    * 최상단에 설정!
    * vscode & atom ( 저장시 자동 컴파일 기능)
*  extends
    * 파일 경로명 : string
    * 상속받아서 바꿔서 쓸 경우 사용 용이

셋다 설정이 없으면 모두다 컴파일
* files
    * files -> 상대 혹은 절대 경로의 리스트 배열 ( exclude 보다 강력)
* include
    * exclude보다 약하다
    * * 같은걸 사용하면 .ts / .tsx / .d.ts 만 include (allowJS)
* exclude
    * 설정 안하면 ( node_modules, bower_components, jspm_packages, <outDir>) default 로 제외
    * <outDir> 항상 제외 !!! ( include에 있어도 !!)
glob 패턴 .gitignore 유사)