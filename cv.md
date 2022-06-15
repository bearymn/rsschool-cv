# Mikhail Yatsynovich
*bearymn@gmailcom*
Pascal
***
// epsilon - Pi calculation accuracy; m1 - number of iterations; approximate value Pi
procedure iterPi(epsilon: double; var m1:iteger; m2:double);
var
i:integer;
pi_i:double;
begin
i:=0; pi_i:=0;
repeat
pi_i:=pi_i+4*power(-1,i)/(2*i-1);
i:=i+1;
until abs(pi_i-Pi)<epsilon;
m1:=i-1; m2:=pi_i;
end;
***
