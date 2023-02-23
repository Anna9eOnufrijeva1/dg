#include <iostream>
#include <vector>
#include <cmath>
using namespace std;

//int main()
//{
//	vector <int> num{ 1, 2, 3, 1, 2 };
//	if (num[0] == 1) cout << "1 element is 1" << endl;
//	if (num[1] == 1) cout << "2 element is 1" << endl;
//	if (num[2] == 1) cout << "3 element is 1" << endl;
//	if (num[3] == 1) cout << "4 element is 1" << endl;
//	if (num[4] == 1) cout << "5 element is 1" << endl;
//	if (num[0] == 4) cout << "1 element is 4" << endl;
//	if (num[1] == 4) cout << "2 element is 4" << endl;
//	if (num[2] == 4) cout << "3 element is 4" << endl;
//	if (num[3] == 4) cout << "4 element is 4" << endl;
//	if (num[4] == 4) cout << "5 element is 4" << endl;
//}

//int main()
//{
//	vector <string> country{ "USA", "UK", "China", "India", "Canada", "Australia" };
//	vector <string> code{ "+1", "+44", "+86", "+91", "+1", "+61" };
//	string num, cod;
//	cout << "Enter your phone code: " << endl;
//	cin >> cod;
//	if (code[0] == cod) cout << country[0] << endl;
//	if (code[1] == cod) cout << country[1] << endl;
//	if (code[2] == cod) cout << country[2] << endl;
//	if (code[3] == cod) cout << country[3] << endl;
//	if (code[4] == cod) cout << country[4] << endl;
//	if (code[5] == cod) cout << country[5] << endl;
//	else cout << "Incorrect code" << endl;
//	cout << "Enter your phone number: " << endl;
//	cin >> num;
//	cout << code[0] + num << endl;
//}

//int main()
//{
//	vector <string> name{ "Anna", "Antons", "Vlads", "Artemijs" };
//	vector <int> mark{ 3, 8, 7, 4 };
//	int num;
//	cout << "Enter your mark: " << endl;
//	cin >> num;
//	if (num == mark[0]) cout << name[0] << endl;
//	if (num == mark[1]) cout << name[1] << endl;
//	if (num == mark[2]) cout << name[2] << endl;
//	if (num == mark[3]) cout << name[3] << endl;
//	else cout << "No data" << endl;
//}

//int main()
//{
//	vector <int> num{ 2, 3, 5, 7, 9 };
//	cout << (num[0] * num[0]) << endl << num[1] * num[1] << endl << num[2] * num[2] << endl << num[3] * num[3] << endl << num[4] * num[4] << endl;
//}

//int main()
//{
//	vector <string> fest{ "Lacplesa diena", "Latvijas Neatkaribas proklamesanas diena", "Martindiena" };
//	vector <string> date{ "11.11.", "18.11.", "11.01." };
//	string yes;
//	cout << "Do you want to see info about holidays?" << endl;
//	cin >> yes;
//	if (yes == "yes") cout << fest[0] << date[0] << endl << fest[1] << date[1] << endl << fest[2] << date[2] << endl;
//	if (yes == "no") cout << "Good Bye!" << endl;
//	else cout << "Invalid answer" << endl;
//
//}

//int main()
//{
//	vector <int> time{ 5, -10, 0, 2, -5, 0 };
//	int a = 0;
//	if (time[0] > 0) a++;
//	if (time[1] > 0) a++;
//	if (time[2] > 0) a++;
//	if (time[3] > 0) a++;
//	if (time[4] > 0) a++;
//	if (time[5] > 0) a++;
//	cout << a << endl;
//}

int main()
{
	vector <int> num{ 16, 4, 33, 8 };
	int a;
	cout << "Insert any number: " << endl;
	cin >> a;
	if (a == num[0]) a++;
	if (a == num[1]) a++;
	if (a == num[2]) a++;
	if (a == num[3]) a++;
	if (a > 0) cout << "Number is in the "
}
