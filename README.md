//3вариант. Базовый уровень.Введите массив символов из 12 элементов Замените каждый символ-цифру на символ '!'.
#include <iostream>
#include <cctype>
using namespace std;

int main()
{
    char s[13];
    cout << "Enter 12 symbols:\n";

    for (int i = 0; i < 12; i++)
        cin >> s[i];

    for (int i = 0; i < 12; i++)
    {
        if (isdigit(s[i])) s[i] = '!';
        cout << s[i] << " ";
    }
    cout << "\n";
    system("pause");
    return 0;
}
