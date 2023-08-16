# brainfuck-exe-js

```javascrip
!(function() {const e = `code here`;let $=Array(3e4).fill(0),a=0,r="";for(let c=0;c<e.length;c++){let t=e[c];switch(t){case">":a=(a+1)%3e4;break;case"<":a=(a-1+3e4)%3e4;break;case"+":$[a]=($[a]+1)%256;break;case"-":$[a]=($[a]-1+256)%256;break;case".":r+=String.fromCharCode($[a]);break;case",":break;case"[":if(0===$[a]){let f=1;for(;f>0;)"["===e[++c]?f++:"]"===e[c]&&f--}break;case"]":if(0!==$[a]){let s=1;for(;s>0;)"]"===e[--c]?s++:"["===e[c]&&s--}}} return Function("return " + r)();})();
```

code hereのところにbrainfuckに変換したjsのコードを書いてください。
ファイル内に書いてよびだせば実行されます。
是非是非。
