# programacion_p5.9
%numeral 5.9
clear all
n=1:1:100;
a=(n-1);
b=(2*pi)^0.5;
c=n.^n-0.5;
d=exp(0.5);
b1=b*c*d;
subplot(2,1,1)
plot(n,a,'b');
title('a=f(n)')
xlabel('vector n')
ylabel('amplitud de a')
subplot(2,1,2)
plot(n,b1,'r')
axis('tight')
box on
