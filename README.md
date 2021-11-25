# pi-cember-ve-alan-hesabi

int main() {
	
//Çemberde alan : pi * r * r
//Çemberde çevre : 2 * r * r
//pi 3.14
printf("Cember Alan ve Cevre Hesabi\n");
printf("**********************************\n");	
float yaricap,pi,alan,cevre;
pi=3.14;
printf("Yaricap Degeri: ");
scanf("%f",&yaricap);

alan=pi*yaricap*yaricap;
cevre=2*pi*yaricap;

printf("Alan: %f\n",alan);
printf("Cevre: %f",cevre);


	return 0;
}
