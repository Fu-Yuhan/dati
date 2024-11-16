<h2>说明</h2>

对于一个字符串来说，定义一次循环移位操作为：将字符串的第一个字符移动到末尾形成新的字符串。<br />
给定两个字符串 $s_1$和 $s_2$，要求判定其中一个字符串是否是另一字符串通过若干次循环移位后的新字符串的子串。例如$CDAA$是由$AABCD$两次移位后产生的新串$BCDAA$的子串，而$ABCD$与$ACBD$则不能通过多次移位来得到其中一个字符串是新串的子串。
<h2>输入格式</h2>

一行，包含两个字符串，中间由单个空格隔开。字符串只包含字母和数字，长度不超过 $30$。

<h2>输出格式</h2>

如果一个字符串是另一字符串通过若干次循环移位产生的新串的子串，则输出"$true$"，否则输出"$false$"。

<h2>样例</h2>
<pre><code class="language-input1">AABCD CDAA</code></pre><pre><code class="language-output1">true</code></pre>