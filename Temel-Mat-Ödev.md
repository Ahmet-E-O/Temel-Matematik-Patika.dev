# Gauss-Jordan Yöntemi ve Eşelon Matris

* Gauss-Jordan yöntemi ile denklem sistemlerini çözebilmek için öncelikli olarak bilmemiz gereken, denklem sistemlerini matris biçiminde gösterebildiğimizdir. Örnek olarak ;

    - 2X + Y = 8
    - X + 3y = 9
    <br></br> 
    - [$~~$ 2 $~~~$  1  $~~~$| $~~$ 8  $~~$]   $~~~$ s1<=>s2  $~~~$ [ $~~$ 1 $~~$  3  $~~~$| $~~$ 9 $~~$]
    - [$~~$ 1 $~~~$  3  $~~~$| $~~$ 9  $~$ ]   $~~~$ ======>$~$   [$~~~$ 2 $~~~$ 1 $~~$| $~~$ 8 $~~$]
    <br ></br>
( Bir sonraki adımda ise elde edilen matris Eşelon Matris haline getirilir.)
    <br></br>
    - -2s1+s2  $~~~~$ [ $~~$ 1 $~~~$ 3 $~~$| $~~$ 9 $~~~$]  $~~~$ -1/5s2  $~~~~~~~$ [$~$ 1 $~$ 3 $~$|$~$ 9 $~$]
    - ======> $~$[$~~$ 0 $~~$ -5 $~$ | $~~$-10 $~$] $~~~$  ======> $~$ [$~$ 0 $~$ 1 $~$|$~$ 2 $~$]
    <br></br>
    - -3s2+s1 $~~~~~~$ [$~~$ 1 $~~$ 0 $~$|$~~$ 3 $~~$]
    - ======> $~~$ [$~~$ 0 $~~$ 1 $~$|$~~$ 2 $~~$]
    <br></br>
    - Böylelikle X = 3, Y = 2 bulunur.
<br></br>
* Denklem Sistemlerini bu method ile çözmeye Gauss-Jordan Yok Etme Methodu denir.
___



           





