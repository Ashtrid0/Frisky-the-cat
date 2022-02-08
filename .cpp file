#include <iostream>
using namespace std;

class Cat
{
	public:
		    void setItsAge(int age); //accessor function
			int getItsAge();  //accessor function
			void Meow();   //general function
	private:
			int itsAge; //data member
};

void Cat::setItsAge (int age)
	{
		itsAge = age;
	}
int Cat::getItsAge()
	{
		return itsAge;
	}
void Cat::Meow()
	{
		cout<<"Meow.\n";
	}

int main()
{
	Cat Frisky; //create a cat
	int age;
		cout<<"Please enter frisky's age:";
		cin>>age;
	Frisky.setItsAge(age);
	Frisky.Meow();
		cout<<"Frisky is a cat who is "
				<<Frisky.getItsAge()<<" years old.\n";
	Frisky.Meow();

return 0;

}

