[2022-07-11]

## 목차

---------------------------------------------------


---------------------------------------------------
* # HTML이란?
HTML이란 Hypertext markup language의 약자이며 하이퍼 텍스트의 방식의 마크업언어이다.

* ## HyperText

HyperText는 사용자가 필요한 정보를 자유롭게 찾아갈 수 있는 비순차적 텍스트를 의미한다.
우리 일상에서도 쉽게 접할 수가 있는데 우리가 웹서핑을 하다 자연스럽게 문자를 클릭하여 링크를 타고 들어가는 기능들을 HyperText라고 한다.

* ## HyperLink

HyperLink는 단순히 텍스트를 넘어 링크를 타고 가는것 뿐만 아닌 이미지나 다른 매체를 통해서도 넘어갈 수 있게 되면서 생긴 단어이다.

* # Tag
Tag는 <>기호로 구성된다. 이러한 태그는 100개 이상이 존재하며, 각각의 역할과 문법에 맞게 사용해야 한다.
일반적으로 Tag는 작성한 텍스트의 앞 뒤에 모두 작성하여 마치 해당 텍스트를 감싸는 듯한느낌으로 작성해야하는데.
<>처럼 시작하는 태그는 Opening tag라고 하고,
</>처럼 태그 내부에/가 있는 태그를 Closing tag라고 한다.  
                                                       ```   <p>안녕하세요</p> ```  
밑에있는 태그를 보면 src,alt와 같은 별도의 속성(attribute)를 지정할 수 있는 태그들이있다.

    <tag name attributte="value">content</tag name>
    <a href= "www.naver.com">go to Naver web</a>
이러한 태그들을 element(요소)라고 부르기도 한다.

* # 실습
          <!DOCTYPE html> <!-- Document type은 html이다.-->
    `````<html lang="en"> <!-- 모든 html 태그의 최상단에 작성해야하는 태그,-->
        <head><!-- 문서의 부가적인 정보(Meta information) 표기-->
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body><!-- 실제 웹 페이지에서 보여질 내용을 작성하는 부분-->
            <article>
                <h1>Best Places To Visit Post-Pandemic</h1>
                Author : Frog, Fox<br> 
                Date: Jun 3, 2021, 4:40am<br>
                <p>"More people are being vaccinated everyday and travel is already top of mind."</p>
                <p>"Suddenly, the whole world feels in reach again, even if travel restrictions haven’t quite been lifted yet."</p>
                
                <img src="images/alentejo_portugal.jpg" alt="포르투칼 알렌테조 풍경" style="width: 480px; height: 270px;">
                <!-- 여우야 뒷 내용을 부탁해~ -->
                <h2>Alentejo, Portugal</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, sed?</p>

                <ul><!-- ul>li*3{text}-->
                    <li>Temperature</li>
                    <li>Heat rating</li>
                    <li>water color</li>
                </ul>

                <a href="http://en.wikipedia.org/wiki/Alentejo">More information</a>
            </article>
            <footer>    
                <p>2021 Webinaa Media LLC. Contact : Fox@Webinaa.com</p>
            </footer>
        </body>
    </html> 
