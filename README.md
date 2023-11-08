# PyScript
HTML 에 파이썬을 끼워넣은 시스템
파이썬 코드를 HTML에서 작성하고 동작시킬 수 있고, PyScript에서 Javascript 라이브러리 들을 부르고, 파이썬으로 모든 웹 개발을 할 수 있음
데이터 사이언스 (혹은 머신러닝 엔지니어) 로써 우리의 데시보드나 모델을 HTML 파일로 공유할 수 있고, 웹브라우저에서 열기만 하면 코드를 실행시킬 수 있음
- streamlit 같은 데모 프레임워크 없이도 웹에서 시연 가능
## PyScript의 원리
CPython 과 WebAssembly/Emscripten은 포팅해주는 Pyodide로 만들어짐
PyScript는 미래에 다른 언어들까지의 지원을 제공할 것
## WebAssembly
파이썬으로 웹사이트를 작성할 수 있게 만들어주는 근원적인 기술
WebAssembly가 원래 개발될때는, 웹 브라우저는 오직 Javascript만 지원했음
2017년에 처음 release 되고 빠르게 2019년 W3C (World Wide Web Consortium) 표준이 됨
사람이 읽을 수 있는 .wat 텍스트 포멧 언어를 브라우저에서 실행시킬 수 있는 .wasm 바이너리 형식으로 전환
모든 언어에서 코드를 작성할 수 있게 허용해주고, WebAssembly로 컴파일할 수 있게 해주고, web browser에서 동작할 수 있게 해줌!

# Bun Script

Bun은 빠르게 모든 작업을 수행할 수 있는 JavaScript 런타임 번들입니다. Bun은 번들러, 트랜스파일러, 태스크 러너 등의 기능을 가지고 있습니다.

Bun은 웹 표준 API를 구현하고 있으며, fetch, ReadableStream, Request, Response, WebSocket, FormData 등을 포함하고 있습니다. Node.js와 비교했을 때, 성능면에서 더 빠른 것으로 알려져 있습니다.

Bun은 JavaScript 코드 번들링을 위한 도구로써, 여러 개의 JavaScript 파일을 하나로 묶어서 웹 애플리케이션의 로딩 시간을 크게 단축시킬 수 있습니다. 또한 코드 번들링 과정에서 minification, obfuscation, compression 등의 작업을 수행하여 코드의 용량을 줄이고 보안성을 높일 수 있습니다.

따라서, Bun은 JavaScript 개발자들이 웹 애플리케이션을 개발할 때 유용하게 사용할 수 있는 도구 중 하나입니다. 

Bun을 사용하면 웹 애플리케이션의 성능을 향상시킬 수 있으며, 코드의 용량을 줄이고 보안성을 높일 수 있습니다. 또한, Bun은 다양한 기능을 제공하기 때문에 개발자들이 더욱 편리하게 작업을 수행할 수 있습니다.

## Bun을 사용 방법

1.Bun을 설치합니다.
2.Bun을 사용하여 코드를 번들링합니다.
3.번들링된 코드를 웹 서버에 업로드합니다.
4.웹 서버에서 번들링된 코드를 로드하여 웹 애플리케이션을 실행합니다.
Bun을 사용하면 개발자들이 더욱 빠르고 효율적으로 작업을 수행할 수 있습니다. 또한, Bun은 다양한 기능을 제공하기 때문에 개발자들이 더욱 편리하게 작업을 수행할 수 있습니다.

웹 애플리케이션을 개발할 때 Bun을 사용하는 것은 매우 유용합니다. Bun을 사용하면 웹 애플리케이션의 성능을 향상시킬 수 있으며, 코드의 용량을 줄이고 보안성을 높일 수 있습니다.

Bun에 대한 자세한 정보는 https://bun.sh/ 에서 확인할 수 있습니다.
