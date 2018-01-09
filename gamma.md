```
Γ(z)
Func
If z<0.5 Then
Return π/(sin(π*z)*Γ(1-z))
ElseIf fPart(z)=0 Then
Return (z-1)!
Else
Return e^(ln(2.5066282756348 +
             225.52558461918/z -
             268.2959738413/(z+1) +
             80.903080693462/(z+2) -
             5.0075786397052/(z+3) +
             0.011468489543478/(z+4)) + 
          (z-1/2)*ln(z+4.65) - z - 4.65)
EndIf
EndFunc
```
