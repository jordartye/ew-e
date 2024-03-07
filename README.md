# ew-e#include <iostream.h>
#include <conio.h>

class vecto
{
	int n;
	int *ptr;
	public:
		vecto(int n);
	~vecto();
	void inputvt();
	void sumvt(int *, int *);
	void displayvt(int*);
	void print();
};

vecto::vecto(int n1)
{
	int i;
	n = n1;
	ptr = new int[n1];
	for (i = 0; i < n; i++) ptr[i] = 0;
}

vecto::~vecto()
{
	delete[] ptr;
}

void vecto::inputvt()
{
	int i;
	cout << "\n input vecto:";
	for (i = 0; i < n; i++)
	{
		cout << "ptu[" << i << "]=";
		cin >> ptr[i];
	}
}
;
	errorcode = graphresult();
	if (errorcode != grOk)
	{
		printf("Graphics error : %s\n", grapherrormsg(errorcode));
		printf("Press any key to halt ...");
		getch();
		exit(1);
void vecto::displayvt(int *p)
{
	int i;
	for (i = 0; i < n; i++) p[i] = ptr[i];
}

void vecto::print()
{
	int i;
	for (i = 0; i < n; i++)
	{
		cout << ptr[i] << " ";
		cout << "\n";
	int n, *p, *p1;
	clrscr();
	cout << "enter sign of vecto :" << '\n';
	cout << "n=";
	cin >> n;
	vecto a(n), b(n), c(n);
	cout << "input vecto a:" << endl;
	b.print();
	cout << "\n display vecto tong c" << endl;
	c.print();
	getch();
}
