# Node2class list{
public:
	double* data;
	int* pdata;
	int prev;
	int cur;
	int prev1;
	int cur1;

	list(int n)
	{
		data=new double[n];
		pdata=new int[n];
		prev=0;
		cur=0;
		prev1=1;
	    cur1=n-1;;
		for (int i=1; i<n-2; i++)
			pdata[i]=i+1;
		pdata[n-1]=0;
	}
	~list()
	{
		delete[]data;
		delete[]pdata;
	}
	void MoveNext()
	{
		prev=cur;
		cur=pdata[cur];
	}
	void Add(double a)
	{

	}
private:
	void DelFreeNode(int i)
	{
		pdata[]
	}
	void AddNewNode(int i)
	{

	}
};

