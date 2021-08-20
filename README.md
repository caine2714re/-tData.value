# -tData.value
Enum $THREE = 3, $FOUR Global $i5 = 5, $i6 = 6
$tData.value(1)      = 1
$tData.value(2)      = 2
$tData.value($THREE) = 3
$tData.value($FOUR)  = 4
$tData.value($i5)    = 5 ;fails
$tData.value($i6)    = 6 ;fails
$tData.value($i5+2)  = 7
$tData.value(8)      = 8
