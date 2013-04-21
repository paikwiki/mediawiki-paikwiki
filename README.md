mediawiki-paikwiki
==================
Paikwiki is based on one of the most popular skin, MonoBook nouveau(Copyright Gabriel Wicke - http://wikidev.net/).
MediaWiki 'paikwiki' style sheet for CSS2-capable browsers.
Copyright chPaik - http://paikwiki.com/
License: GPL (http://www.gnu.org/copyleft/gpl.html)

notice
======
 * Cause' I have some language problem, some part of this document has written by my native language, Korean.
 * But it doesn't have any important contents.
 * You can use paikwiki skin freely.
 * Enjoy it! 


개 요 
=====
1. mediawikiSkin "paikwiki"는 모노북 스킨을 기초로 하여 제작한 스킨입니다.
2. 스마트폰, 태블릿, PC 등 여러 환경에 적합한 스킨을 만들고 있습니다.
3. 프로젝트 시작일 : 2013.04.19

버전 정보
=========
1. 버전0.3 : 2013.04.21 
   - div#p-personal 아래에 div.generated-sidebar 떠있도록 설정. 모바일에서 폰트 사이즈 120%.
2. 버전0.2 : 2013.04.20
   - 로고 위치 지정, 상단에 div#p-personal과 div#p-cactions 떠있도록 설정. div#p-personal 가로 100%, 세로 80px.
3. 버전0.1 : 2013.04.19
   - 레이아웃 구성, paikwiki.php에서 div#column-one을 div#content보다 먼저 출력하도록 수정.

참고 사항
=========
1. 상단메뉴 부분 중 로고 아래의 막대메뉴는 mediawiki:sidebar의 div.generated-sidebar에 CSS를 적용했습니다.
   따라서 같은 클래스를 사용하는 다른 메뉴가 있으면 중복될 수 있습니다.
   예제사이트(paikwiki.com)에서는 Extension:CategoryTagCloud를 사용하고 있는데,
   상단에 중복되는 현상이 있어 CSS에서 수정했습니다.
2. div의 z-index가 깔끔하게 정리되어 있지 못한 상황입니다. 추후 다듬을 예정입니다.
3. main.css 하단부에는 모바일 디바이스를 위한 CSS와 파이킈키에서 사용하기 위한 CSS가 함께 있습니다. 
   스킨 적용시 참고하세요.
