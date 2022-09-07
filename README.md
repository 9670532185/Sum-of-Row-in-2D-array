# Sum-of-Row-in-2D-array
#include<iostream>
using namespace std;

int main()
{
	int row,col;
	cout<<"Enter row and col"<<endl;
	cin>>row>>col;
	int arr[row][col];
	for(int i=0;i<row;i++)
	{
		for(int j=0;j<col;j++)
		{
			//cout<<"Enter "<<row*col<<"Elements"<<endl;
			cin>>arr[i][j];
		}
	}
		for(int i=0;i<row;i++)
	{
		for(int j=0;j<col;j++)
		{
		//	cout<<"Enter "<<row*col<<"Elements"<<endl;
			cout<<arr[i][j];
		}
		cout<<endl;
	}
//	if(row==0)
//	{
//		return 0;
//	}

		for(int i=0;i<row;i++)
	
		{
		int sum=0;
		for(int j=0;j<col;j++)
		{
		
		
				
		//	cout<<"Enter "<<row*col<<"Elements"<<endl;
			sum=sum+arr[i][j];
		
		}
			 cout<<sum<<endl;
			
			// return 0;
		
		
	}
	
	//	cout<<endl;
//	cout<<endl;
}
