# UPPERCASE.js
UPPERCASE.js는 API가 대문자로 이루어진 JavaScript 라이브러입니다. OOP, UTIL, BOX 세가지 파트로 나뉩니다. [UPPERCASE.IO](http://UPPERCASE.IO) 등 다양한 프로젝트에서 사용됩니다.

##### Document & Testcase
http://UPPERCASE.IO/#UDOC/UPPERCASE.js

##### Version
1.3

##### License
UPPERCASE.js의 License는 이하 문서를 따릅니다.<br>
https://github.com/BTNcafe/UPPERCASE.js/blob/master/LICENSE.md


### node.js에서 사용하기

###### install
	npm install uppercase.js

###### example
	// require('uppercase.js');는 프로그램 전체에서 한번만 실행합니다.
	require('uppercase.js');
	
	m = METHOD({
		run : function() {
			console.log('test');
		}
	});
	
	m();


### 브라우저에서 사용하기

###### install
	<script>
		global = window;
	</script>
	<script src="UPPERCASE.js"></script>

###### install (each part)
	<script>
		global = window;
	</script>
	<script src="UPPERCASE-OOP.js"></script>
	<script src="UPPERCASE-UTIL.js"></script>
    <script src="UPPERCASE-BOX.js"></script>

###### example
    <!doctype html>
    <html>
        <head>
            <meta charset="UTF-8">
            <title>UPPERCASE.js Example</title>
        </head>
        <body>
            <p>
                UPPERCASE.js Example
            </p>
            <script>
                global = window;
            </script>
            <script src="UPPERCASE.js"></script>
            <script>
                window.onload = function() {
                    OBJECT.init();

                    m = METHOD({
                        run : function() {
                            console.log('test');
                        }
                    });

                    m();
                };
            </script>
        </body>
    </html>



## UPPERCASE-OOP.js
객체지향 프로그래밍을 하기 위한 JavaScript 라이브러리입니다.<br>
http://UPPERCASE.IO/#UDOC/UPPERCASE.js/OOP
- UPPERCASE-UTIL.js이 필요합니다.

## UPPERCASE-UTIL.js
다양한 기능을 제공하는 JavaScript 유틸리티 라이브러리입니다.<br>
http://UPPERCASE.IO/#UDOC/UPPERCASE.js/UTIL
- UPPERCASE-OOP.js가 필요합니다.

## UPPERCASE-BOX.js
JavaScript로 모듈 프로그래밍을 할 수 있도록 지원하는 라이브러리입니다.<br>
http://UPPERCASE.IO/#UDOC/UPPERCASE.js/BOX
- UPPERCASE-OOP.js가 필요합니다.
- UPPERCASE-UTIL.js이 필요합니다.



2014 ⓒ BTNcafe · http://www.btncafe.com · contact@btncafe.com
