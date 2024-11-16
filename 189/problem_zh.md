<h2>说明</h2>

某医院想统计一下某项疾病的获得与否与年龄是否有关，需要对以前的诊断记录进行整理，按照 $0-18$、$19-35$、$36-60$、$61$以上（含 $61$）四个年龄段统计的患病人数占总患病人数的比例。
<h2>输入格式</h2>

共 $2$ 行，第一行为过往病人的数目 $n$($0 < n ≤ 100$)，第二行为每个病人患病时的年龄，年龄为不超过 $100$ 的非负整数。

<h2>输出格式</h2>

照 $0-18$、$19-35$、$36-60$、$61$ 以上（含 $61$）四个年龄段输出该段患病人数占总患病人数的比例，以百分比的形式输出，精确到小数点后两位。每个年龄段占一行，共四行。

<h2>样例</h2>
<pre><code class="language-input1">10
1 11 21 31 41 51 61 71 81 91</code></pre><pre><code class="language-output1">20.00%
20.00%
20.00%
40.00%</code></pre>