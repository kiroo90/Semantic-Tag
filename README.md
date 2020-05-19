# Semantic-Tag
개인용
<pre>
<code>

      <header>
          <h1>시멘틱 태그 정리</h1>
          <nav>
              <ul>
                  <li>header</li>
                  <li>nav</li>
                  <li>ul list의 부모</li>
                  <li>li list의 item</li>
              </ul>
          </nav>
      </header>
  
    <aside>
        <p>
            aside 페이지 콘텐츠를 제외한 콘텐츠를 정의 <br>
            링크,광고,사이드바 등
        </p>
    </aside>

        <section>
            <article>
                <hgroup>
                    <h2>section&article</h2>
                    <h3>소제목이 들어가야함 h2~h5</h3>
                    <h3>hgroup 제목과 부제목을 묶는 태그 가독성</h3>
                </hgroup>
                <p>section 문서의 구역을 정의 </p>
                <p>article 내용을 정의 </p>
                <p>p 문단,br 줄바꿈 하지만 br를 남용하지말자.</p>
            </article>
            <article>
                <h2>dl&dd</h2>
                <dl>
                    <dd>dl 설명형 목록의 부모</dd>
                    <dd>dd 설명형 목록의 item</dd>
                    <dd><strong>strong</strong>중요성을 강조</dd>
                    <dd><b>b</b>텍스트와 구별할때</dd>
                    <dd><b>em</b>강조</dd>
                    <dd><mark>mark</mark>단순 참고용</dd>
                </dl>
                <figure>
                    <img src="" alt="figure 이미지,음원,동영상등 해당 콘텐츠에 대한 설명">
                    <figcaption>figure 요소에 대한 제목(설명)</figcaption>
                </figure>
            </article>
        </section>

    <footer>
        <address>
            address 주소 <br>
            검색엔진이 어떤 기업의 주소를 찾을때 footer의 address를 찾는다. <br>
            이텔릭체는 CSS로 수정가능.
        </address>
    </footer>
