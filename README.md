# MaxSleep
$sText = "Can't be this"  $iMaxSleepTime = 10000  $iSleep = 0  do while $sText &lt;> "Can't be this"      sleep(1000)      $iSleep += 1000      if $iSleep > $iMaxSleepTime then ExitLoop  loop
