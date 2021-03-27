float func (float a, float b) {
return a/b;
04 void main (){
float a, b=2, c=4;

a=b;

b=c;

c=b* func (b, a);

printf("a=s.1f\tb=$.1f\te=s. 1f\n", a,b,c);
