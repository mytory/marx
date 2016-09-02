---
id: 45
title: 구글 맞춤 검색(CSE)에 추가된 ‘색인생성’ 기능 (번역)
date: 2008-12-02T05:59:32+00:00
author: mytory
layout: post
guid: http://work.local/marx.mytory.net/2008/12/02/%ea%b5%ac%ea%b8%80-%eb%a7%9e%ec%b6%a4-%ea%b2%80%ec%83%89cse%ec%97%90-%ec%b6%94%ea%b0%80%eb%90%9c-%ec%83%89%ec%9d%b8%ec%83%9d%ec%84%b1-%ea%b8%b0%eb%8a%a5-%eb%b2%88%ec%97%ad/
permalink: /archives/45
categories:
  - 웹
tags:
  - cse
  - Google
  - 검색엔진 최적화
  - 구글
  - 구글 맞춤 검색
  - 구글 맞춤 검색 색인생성
  - 구글검색
  - 맞춤 검색
  - 색인생성
---
<span style="FONT-WEIGHT: bold"></span></p> 

<div class="txc-textbox" style="BORDER-RIGHT: rgb(193,193,193) 1px dashed; PADDING-RIGHT: 10px; BORDER-TOP: rgb(193,193,193) 1px dashed; PADDING-LEFT: 10px; PADDING-BOTTOM: 10px; BORDER-LEFT: rgb(193,193,193) 1px dashed; PADDING-TOP: 10px; BORDER-BOTTOM: rgb(193,193,193) 1px dashed; BACKGROUND-COLOR: rgb(238,238,238)">
  <p>
    이  글은 구글 맞춤 검색<a title="[http://www.google.co.kr/cse]로 이동합니다." href="http://www.google.co.kr/cse" target="_blank">(CSE : Custom Search Engine)</a> 사용자들을 위한 것이다. 아마도 대형 블로그를 운영하고 있는 사람들은 이 맞춤검색을 종종 사용할 것이다.
  </p>
  
  <p>
    그러나 대체로 블로그들은 rss만 웹마스터 툴의 사이트맵에 등록해 놓으면 색인이 잘 된다. 그래서 굳이 이런 ‘색인생성(맞춤 색인)’ 기능을 사용할 필요는 없을 듯하다.
  </p>
  
  <p>
    내 생각에 ‘색인생성(맞춤 색인)’ 기능 등에 대한 설명이 필요한 사람들은 중간 규모의 웹사이트를 운영하는 사람들이다. 예를 들면 대학 언론사나 교지 같은 곳, 시민단체나 중소기업 말이다.
  </p>
  
  <p>
    그런 사이트들은 검색엔진에 최적화돼있지도 않고, 내부 검색엔진이 있더라도 성능이 썩 좋지 않다. (내 생각엔 내부 검색엔진과 구글 맞춤검색을 동시에 활용하면 가장 좋은 효과를 볼 수 있을 것 같다.) 이런 사이트들이 구글 맞춤 검색을 이용해서 검색의 효과를 높이는 동시에 구글 검색에 더 많은 페이지가 잡히도록 조치할 수 있다고 생각한다.
  </p>
  
  <p>
    (물론, 구글은 맞춤 검색에 페이지가 잡힌다고 해도 구글 검색에 즉각 반영되는 것은 아니라고 설명하고 있지만 곧이곧대로 들리지는 않는다. 정보가 있으면 활용하는 게 당연하지 않을까? 물론, 어떤 기준은 있겠지만 <strong>내 생각엔</strong> 맞춤검색에 색인된 페이지가 늘어나면 구글 메인 검색에도 잡히는 페이지가 늘어나는 게 자연스럽다.)
  </p>
  
  <p>
    구글 맞춤 검색에는 원래 ‘색인생성(맞춤 색인)’을 제출하는 기능이 없었는데 최근에 생겼다. (일종의 맞춤검색용 <a title="외부링크 [검색엔진 최적화의 기본 : 구글에 사이트맵 등록하기 1]로 이동합니다." href="http://www.seo-korea.com/10" target="_blank">구글 사이트맵(sitemap)</a>이라고 생각하면 될 듯하다.) 그래서 아직 설명 부분도 번역이 안 된 듯하다. 사실 맞춤 검색 자체가 번역 부분이 늦다.
  </p>
  
  <p>
    구체적 사용 방법은 실습해본 후 올리겠다. 일단 급한대로 친구에게 부탁해서 번역을 했다. 번역본을 참고하면 좋을 듯하다.
  </p>
  
  <p>
    번역이 매끄럽지는 못하다. 번역자의 탓이 아니라 전적으로 내가 시간이 없어 다듬지 못한 탓이다. 그러나 맞춤 검색을 최적화하기 위해 이리저리 디벼 본 사람들이라면 어느 정도 이해할 것이라고 생각하며, 잘 이해가지 않더라도 직접 도전해보실 것이라고 생각한다. (혹, 추가할만한 정보가 있으면 댓글이나 트랙백으로 남겨 주시라.)
  </p>
  
  <p>
    다음은 <a href="http://www.google.com/support/customsearch/bin/topic.py?hl=ko&topic=16792" target="_blank">Custom Search Help의 On-demand Indexing 부분</a>을 번역한 것이다.
  </p>
</div>

<span style="FONT-WEIGHT: bold">‘색인생성(맞춤 색인)’이란 무엇인가?</span>

‘색인생성(맞춤 색인)’을 이용하면 제출한 사이트의 페이지를 빠르게 색인할 수 있다. ‘색인생성(맞춤 색인)’을 이용하면 제출한 페이지들의 가장 최신 버젼들을 24시간 내로 <a title="[http://www.google.co.kr/cse]로 이동합니다." href="http://www.google.co.kr/cse" target="_blank">맞춤 검색 엔진(CSE)</a>에 색인할 수 있다.

<span style="FONT-WEIGHT: bold"></span><img src="http://work.local/marx.mytory.net/wp-content/uploads/1/4934cd6f73727AH.JPG" class="aligncenter" width="610" height="457" alt="최근 구글 맞춤 검색에서 서비스하기 시작한 ‘색인생성’" filename="on-demand_indexing.JPG" filemime="" />

<span style="FONT-WEIGHT: bold">어떻게 이용하나?</span>

우선, <a title="[https://www.google.com/accounts/ServiceLogin?service=sitemaps&passive=true&nui=1&continue=http%3A%2F%2Fwww.google.com%2Fwebmasters%2Ftools%2Fdashboard%3Fhl%3Dko&followup=http%3A%2F%2Fwww.google.com%2Fwebmasters%2Ftools%2Fdashboard%3Fhl%3Dko&hl=ko]로 이동합니다." href="https://www.google.com/accounts/ServiceLogin?service=sitemaps&passive=true&nui=1&continue=http%3A%2F%2Fwww.google.com%2Fwebmasters%2Ftools%2Fdashboard%3Fhl%3Dko&followup=http%3A%2F%2Fwww.google.com%2Fwebmasters%2Ftools%2Fdashboard%3Fhl%3Dko&hl=ko" target="_blank">웹마스터 도구</a>에서 CSE의 <a title="외부링크 [검색엔진 최적화의 기본 : 구글에 사이트맵 등록하기 1]로 이동합니다." href="http://www.seo-korea.com/10" target="_blank">사이트 맵</a>을 올바르게 만들어야 한다. 사이트맵에 관해서는 Webmaster Help Center를 참고하라. 한 계정으로 사용자 검색 엔진과 사이트 맵을 연결할 것을 권장한다. 물론 사이트맵의 주소를 안다면 다른 계정으로 해도 상관 없다.

사이트맵을 만들면, <a title="[http://www.google.co.kr/cse]로 이동합니다." href="http://www.google.co.kr/cse" target="_blank">CSE</a> 계정으로 로그인 하고 다음의 절차를 따르라.

1. CSE 제어판(control panel)에서 색인생성(Indexing) 탭으로 가라
  
2. 색인생성(On-demand indexing)에서, Select a Sitemap 펼침 메뉴에서 사이트맵을 선택하라. 올바로 만든 사이트맵만 그 메뉴에 뜰 것이다.
  
3. Index Now 버튼을 누른다.

Index Now를 누르면, 구글은 사이트맵에 기록된 페이지들의 목록을 <a title="[http://www.google.co.kr/cse]로 이동합니다." href="http://www.google.co.kr/cse" target="_blank">CSE</a>의 색인에 작성한다. 이 목록은 빠른 크롤링과 색인에 이용된다. 몇시간 후에 이 페이지들이 <a title="[http://www.google.co.kr/cse]로 이동합니다." href="http://www.google.co.kr/cse" target="_blank">CSE</a>의 검색 결과에 포함되는 것을 볼 수 있을 것이다. 사이트맵에 기재된 모든 페이지는 그 수가 ‘색인생성(맞춤 색인)’의 할당량을 넘지 않으면 24시간 내에 등록된다. 만약 할당량을 넘으면, 사이트맵에 기재된 정보를 통해 우선순위를 따질 것이다. 이 우선순위에 관해서는 Webmaster Help Center에 있는 이 글을 보라.

<a href="http://www.google.com/support/webmasters/bin/answer.py?answer=71936&topic=13452#prioritize" target="_blank">http://www.google.com/support/webmasters/bin/answer.py?answer=71936&topic=13452#prioritize</a>

**얼마나 많은 페이지 ‘색인생성(맞춤 색인)’으로 검색 엔진에 등록시킬 수 있는가?**

모든 공짜 CSE는 10 페이지가 할당된다. 여러개의 검색 엔진이 있다면, 각 엔진마다 그만큼씩 할당된다. 구글의 경우 다음과 같다.</p> 

<table width="400" align="center" border="1">
  <tr>
    <td>
      계정 종류
    </td>
    
    <td>
      검색엔진 당 ‘색인생성(맞춤 색인)’ 페이지
    </td>
  </tr>
  
  <tr>
    <td>
      공짜
    </td>
    
    <td>
      10
    </td>
  </tr>
  
  <tr>
    <td>
      $100(/1년)
    </td>
    
    <td>
      250
    </td>
  </tr>
  
  <tr>
    <td>
      $500
    </td>
    
    <td>
      1000
    </td>
  </tr>
  
  <tr>
    <td>
      $850
    </td>
    
    <td>
      2500
    </td>
  </tr>
  
  <tr>
    <td>
      $2250
    </td>
    
    <td>
      5000
    </td>
  </tr>
  
  <tr>
    <td>
      기타
    </td>
    
    <td>
      연락 바람
    </td>
  </tr>
</table>

We reserve the right to change these limits in response to usage and capacity constraints.
  
(우리는 사용과 수용능력 제한에 응답하여 이런 한계를 바꿀 권리를 보장한다. &#8211; 무슨 말인지는 모르겠지만 사용량 등에 따라 저 수치가 달라질 수 있다는 뜻인 것 같네요.)

<span style="FONT-WEIGHT: bold">어떻게 사이트 업데이트를 하면 ‘색인생성(맞춤 색인)’을 하도록 하나?</span> 

‘색인생성(맞춤 색인)’은 페이지를 추가하는 경우와 기존 페이지를 업데이트하는 경우, 두 경우에 사용된다. 

‘색인생성(맞춤 색인)’에 제출하는 새 페이지들은 <a title="구글에서 검색엔진에 등록하는 것">크롤링</a>의 대상이 될 것이고, 메인 구글 색인(where they&#8217;ll remain available to return as results in your search engine but can be replaced in your on-demand Sitemap)에 포함될 것이다.  새 페이지가 색인에 포함되도록 하려면(determined), Webmaster Tools 계정에서 페이지의 URL을 체크하거나, Goolge.com에서 검색해보라.

만약 내용은 바꾸되 URL을 바꾸지 않는다면, 사이트맵에 기록된 URL을 그대로 두면 된다. 언제 내용이 바뀌었는지 정하려면, 사이트맵에 기록된 lastmod 태그를 사용하라. 이에 대해서는 Webmaster Help Center를 참고하라.

‘색인생성(맞춤 색인)’으로 등록할 수 있는 페이지의 수는 제한되어있다. 따라서 중요한 페이지가 등록되게 하려면, 사이트 맵에서 정확한 최근 수정 날짜와 우선순위를 활용할 것을 강력히 권장한다. 

<span style="FONT-WEIGHT: bold">만약, 내 검색 엔진이 내 소유의 여러 도메인에 걸쳐져 있다면 어떻하나?</span>

‘색인생성(맞춤 색인)’은 현재 한번에 하나의 사이트 맵만을 수용한다. 따라서 여러 도메인에 있는 페이지를 ‘색인생성(맞춤 색인)’하려면, 이 페이지를 모두 기록한 사이트 맵을 쓰면 된다. 그 사이트에 대한 소유권만 있다면 가능하다. 사이트를 넘나드는 사이트맵에 대해서는 Webmaster Help Center를 보라.

<span style="FONT-WEIGHT: bold">내 소유가 아닌 도메인의 페이지를 포함시킬 수는 있나?</span>

(유추하면 됨)

<span style="FONT-WEIGHT: bold">새 사이트 맵을 제출하면, 내 검색엔진은 옛날꺼를 버리나?</span>

만약 CSE나 GSS가 새 페이지를 수용할 만한 [여분의] 할당량이 있다면, 버려지는 페이지는 없을 것이다. 만약 제한을 넘으면, ‘색인생성(맞춤 색인)’에서 페이지를 없앨테다. 우리는 사이트 맵에서 설정한 우선 순위와 최근 수정일을 통해 가장 덜 중요한 페이지들만을 없애도록 노력하고 있다.

할당량을 얼마나 쓰고 있는지를 보려면, 검색엔진 control panel의 Indexing을 보라. On-demand indexing을 보면, 사이트맵의 주소와 색인 상태, 남은 할당량을 볼 수 있다. 

<span style="FONT-WEIGHT: bold">‘색인생성(맞춤 색인)’에 등록한 페이지는 Google.com 검색으로 잡히나?</span>

‘색인생성(맞춤 색인)’은 CSE에 맞춘 특별한 색인이다. Goolge메인 검색엔진의 색인 과정의 작동 방식은 이와 다르다. 따라서 꼭 된다는 보장은 없다. ‘색인생성(맞춤 색인)’에 페이지를 제출한다고 해서 메인 구글의 색인이나 랭킹에 변화가 생기진 않는다.

<span style="FONT-WEIGHT: bold">‘색인생성(맞춤 색인)’ 페이지의 목록 갱신</span>

새로운 페이지 혹은 다른 페이지를 ‘색인생성(맞춤 색인)’하도록 하려면, 사이트 맵을 업데이트 하거나 새로운 사이트 맵을 올려라. CSE control panel로 돌아가서 갱신한 사이트 맵을 선택하고 Index Now 버튼을 눌러라. 한번 ‘색인생성(맞춤 색인)’을 한 후 24시간 내에는 더 색인을 할 수 없다.

<span style="FONT-WEIGHT: bold">사이트맵에 URL을 추가하고 ‘색인생성(맞춤 색인)’에 제출했다. 근데 왜 검색에 안잡히나?</span>

거기에는 여러가지 이유가 있다.

&#8211; 그 페이지를 크롤하려고 보니 없거나 에러가 난 경우. 

&#8211; 이미 크롤한 경우. 

&#8211; 너무 큰 경우.(예컨대, 덩치가 큰 PDF파일)

사이트맵에 오류가 있을 수도 있다. 사이트맵 오류를 보려면 이 기사를 보시오 : <a href="http://www.google.com/support/webmasters/bin/answer.py?answer=35738" target="_blank">http://www.google.com/support/webmasters/bin/answer.py?answer=35738</a>

**마지막 두 질문은 생략**

<p align="right">
  번역 lww
</p>

<div class="txc-textbox" style="BORDER-RIGHT: rgb(193,193,193) 1px dashed; PADDING-RIGHT: 10px; BORDER-TOP: rgb(193,193,193) 1px dashed; PADDING-LEFT: 10px; PADDING-BOTTOM: 10px; BORDER-LEFT: rgb(193,193,193) 1px dashed; PADDING-TOP: 10px; BORDER-BOTTOM: rgb(193,193,193) 1px dashed; BACKGROUND-COLOR: rgb(238,238,238)">
  번역은 여기까지다. 중소형 웹사이트 관리자분들께 도움이 됐으면 하는 바람이다. 구글 맞춤 검색 활용은 앞으로도 계속 할 예정이니 공유할 정보가 있으면 함께 나눴으면 한다.</p> 
  
  <p>
    여기부터는 2008년 12월 8일에 추가한 부분이다. 조금 더 사용하면서 추측하게 된 것이 있었다. 그래서 적은 것이 다음 포스트다.
  </p>
  
  <p style="TEXT-ALIGN: center">
    <a title="[http://spar2003.tistory.com/36]로 이동합니다." href="http://spar2003.tistory.com/36" target="_blank">구글 맞춤 검색(CSE)에 추가된 ‘색인생성’ 기능 활용</a>
  </p>
</div>