## pyscript
HTML 에 파이썬을 끼워넣은 시스템
파이썬 코드를 HTML에서 작성하고 동작시킬 수 있고, PyScript에서 Javascript 라이브러리 들을 부르고, 파이썬으로 모든 웹 개발을 할 수 있음
데이터 사이언스 (혹은 머신러닝 엔지니어) 로써 우리의 데시보드나 모델을 HTML 파일로 공유할 수 있고, 웹브라우저에서 열기만 하면 코드를 실행시킬 수 있음
- streamlit 같은 데모 프레임워크 없이도 웹에서 시연 가능
#PyScript의 원리
CPython 과 WebAssembly/Emscripten은 포팅해주는 Pyodide로 만들어짐
PyScript는 미래에 다른 언어들까지의 지원을 제공할 것
#WebAssembly
파이썬으로 웹사이트를 작성할 수 있게 만들어주는 근원적인 기술
WebAssembly가 원래 개발될때는, 웹 브라우저는 오직 Javascript만 지원했음
2017년에 처음 release 되고 빠르게 2019년 W3C (World Wide Web Consortium) 표준이 됨
사람이 읽을 수 있는 .wat 텍스트 포멧 언어를 브라우저에서 실행시킬 수 있는 .wasm 바이너리 형식으로 전환
모든 언어에서 코드를 작성할 수 있게 허용해주고, WebAssembly로 컴파일할 수 있게 해주고, web browser에서 동작할 수 있게 해줌!

##bunscript
