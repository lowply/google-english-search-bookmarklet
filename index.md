# Google English search bookmarklet

このリンクをブックマークバーにドラッグ&ドロップしてください。

[Google English](javascript:%28%20function%28%29%7B%20g%3D%22http:%2F%2Fwww%2Egoogle%2Ecom%2Fsearch%3Fhl%3Den%26%22%3B%20u%3Ddocument%2EURL%3B%20s%3Du%2EindexOf%28%22%26q%3D%22%29%2B1%3B%20if%28s%3D%3D0%29%7Bs%3Du%2EindexOf%28%22q%3D%22%29%7D%3B%20e%3Du%2EindexOf%28%22%26%22%2Cs%29%3B%20if%28e%3D%3D%2D1%29%7Be%3Du%2Esearch%28%2F%24%2F%29%7D%3B%20location%2Ehref%3Dg%2Bu%2Eslice%28s%2Ce%29%3B%20%7D%20%29%20%28%29%3B%20)

詳しくは [github.com/lowply/google-english-search-bookmarklet](https://github.com/lowply/google-english-search-bookmarklet) まで。
