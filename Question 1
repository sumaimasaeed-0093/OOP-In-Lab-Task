#include <iostream>
#include <string>
using namespace std;

class Book {
private:
    string title;
    string author;
    double price;

public:
    Book() : title("Untitled"), author("Anonymous"), price(0.00) {}

    Book(string t, string a = "Unknown", double p = 0.00)
        : title(t), author(a), price(p) {}

    Book(const Book &b)
        : title(b.title), author(b.author), price(b.price) {}

    void display() const {
        cout << "Title  : " << title << endl;
        cout << "Author : " << author << endl;
        cout << "Price  : $" << price << endl;
    }
};

int main() {
    Book b1;

    Book b2("1984", "Enid Blyton", 26.99);

    Book b3(b2);

    Book b4("World's Bestseller");

    b1.display();
    b2.display();
    b3.display();
    b4.display();

    return 0;
}
