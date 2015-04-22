# kadai2
　

●練習問題2.1
　

>>> zipcode=02492
　

  File "<stdin>", line 1
　

    zipcode=02492
　

                ^
SyntaxError: invalid token
　

>>> zipcode=02132
　

>>> zipcode
　

1114
　


何が起きているか分かるかな？
　

→先頭に0をつけると8進数表記、0xをつけると16進数表記になる。0をつけないとそのまま出力される。
　



●練習問題2.2
　

5
　

x = 5
　

x + 1
　

→このままだと何も出力されない。
　


print 5
　

x = 5
　

print x + 1
　

→printをつけると5,6が出力される
　



●練習問題2.3
　

>>> width = 17
　

>>> height = 12.0
　

>>> delimiter = '.'
　

>>> width/2
　

8
　

>>> type(width/2)
　

<type 'int'>
　

>>> width/2.0
　

8.5
　

>>> type(width/2.0)
　

<type 'float'>
　

>>> height/3
　

4.0
　

>>> type(height/3)
　

<type 'float'>
　

>>> 1 + 2 * 5
　

11
　

>>> type(1 + 2 * 5)
　

<type 'int'>
　

>>> delimiter * 5
　

'.....'
　

>>> type(delimiter * 5)
　

<type 'str'>
　



●練習問題2.4
　

1.
　

>>> r=5
　

>>> pi=3.141592653597932
　

>>> (4*pi*r**3)/3
　

523.5987755996554
　

2.
　

>>> (24.95*0.6)*60+3+(0.75*59)
　

945.4499999999999
　

3.
　

>>> a=8.25
　

>>> b=7.2
　

>>> a+b*3+a
　

38.1
　


6:52amに38.1分(38分06秒)を足す
　

7:30:06
　


