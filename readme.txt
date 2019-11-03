hw2

test2.ek有一些地方语法本来就有问题（？）

$x = $a + $b - $c / $a * $b;

$x是int, $a + $b - $c / $a * $b是float, 但是implicit casts应该是不支持的

if ($xyz > -$xy && $a < $b || ($c == $a || !$x)) 

$x是int, !$x 感觉不合法...
