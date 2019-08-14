### 組合總數
(一) 由 $n$ 個相異物件中，每次取 1 個，2 個， 3 個， $\cdots n$ 個之組合總數為 $2^{n}-1$。

<span style="color: violet">證</span> 吾人對於 $n$ 個物件中，每一物件皆有取與不取兩種處理方法。則對於 $n$ 個相異物件，共有 $(1+1)(1+1)\cdots(1+1)$ 即 $2^n$ 種選取法，但其中含有一種皆不取之法應棄去，因得至少取一個，至多取全部之方法為 $2^n-1$。即
$$2^n-1=_nC_1+_nC_2+\cdots+_nC_n$$

<span style="color: violet">別證</span> $\because (a+b)^n=_nC_0a^n+_nC_1a^{n-1}b+_nC_2a^{n-2}b^2+\cdots+_nC_nb^n$

令 $a=b=1$ 代入

$$2^n=_nC_0+_nC_1+_nC_2+\cdots+_nC_n$$
$\therefore\qquad _nC_1+_nC_2+\cdots+_nC_n=2^n-1$

