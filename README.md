  **[Tutorial]**
  <summary>
  1º CTRL + SHIFT + B
  </summary>
  <summary>
  2º ARRASTE O CODIGO A BAIXO PARA A BARRA DE TAREFAS
  </summary>
  <summary>
  3º VÁ PARA O KHAN ACADEMY E CLIQUE NO BOOKMARK
  </summary>

  
```js
javascript:let originalParse=JSON.parse;JSON.parse=function(e,t){let a=originalParse(e,t);try{a&&a.data&&"object"==typeof a.data&&Object.keys(a.data).forEach((e=>{let t=a.data[e];"assessmentItem"===e&&t&&t.item&&"object"==typeof t.item&&(t.item.itemData=JSON.stringify({answerArea:{calculator:!1,chi2Table:!1,periodicTable:!1,tTable:!1,zTable:!1},hints:[{content:"$\\\\begin{align}\\\\n\\\\left(\\\\dfrac{z^{4}}{6^{2}}\\\\right)^{-3}&=\\\\dfrac{\\\\left(z^{4}\\\\right)^{-3}}{\\\\left(6^{2}\\\\right)^{-3}}\\\\n\\\\end{align}$",images:{},replace:!1,widgets:{}},{content:"$\\\\begin{align}\\\\n\\\\phantom{\\\\left(\\\\dfrac{z^{4}}{6^{2}}\\\\right)^{-3}}&=\\\\dfrac{z^{(4)(-3)}}{6^{(2)(-3)}}\\\\n\\\\\\\\n&=\\\\dfrac{z^{-12}}{6^{-6}}\\\\n\\\\\\\\n&=\\\\dfrac{6^{6}}{z^{12}}\\\\n\\\\end{align}$",images:{},replace:!1,widgets:{}}],itemDataVersion:{major:0,minor:1},question:{url:"https://github.com/MFernandesSilva",images:{},widgets:{"radio 1":{alignment:"default",graded:!0,options:{choices:[{content:"CERTO",correct:!0},{content:"ERRADO",correct:!1}],deselectEnabled:!1,displayCount:null,hasNoneOfTheAbove:!1,multipleSelect:!1,onePerLine:!0,randomize:!1},static:!1,type:"radio",version:{major:1,minor:0}}}}}))}))}catch(e){console.error("Error processing JSON:",e)}return a},location.softReload=()=>{const e=document.getElementsByTagName("html")[0].outerHTML;document.open(),document.write(e),document.close()},location.softReload();
```  
