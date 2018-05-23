# laba_2

#include <stdio.h>

int main() {
	float a, b, c;
	printf ("====Discriminant calculator===\n");
	printf ("Enter a:");
	scanf ("%f", &a);
	printf ("Enter b:");
	scanf ("%f", &b);
	printf ("Enter c:");
	scanf ("%f", &c);	
	float D = b*b-4*a*c;
	if (D > 0) {
		printf ("D = ");
		printf ("%f", D);
		printf (" (equation has two roots)\n");
	}
	if (D == 0) {
		printf ("D = ");
		printf ("%f", D);
		printf (" (equation has single root)\n");
	}
	if (D < 0) {
		printf ("D = ");
		printf ("%f", D);
		printf (" (equation has no real roots)\n");
	}
	return 0;
}
