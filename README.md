# Textbook
/*void random(long n,double e[],double avr,double var)
{
	long i;
	double a,b,c;
	srand((unsigned)time(NULL));
	for(i=0;i<n;i++)
	{
		c=rand();
		if((c-0.000001)<0)
		{ 
			i--;
			continue;
		}
		a=sqrt(-2.0*log(c/32767.0));
		b=2*3.14159265*rand()/32767.0;
		e[i]=var*a*cos(b)+avr;
	}
}*/
