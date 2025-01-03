#include <iostream>

int main() { 
  int totalAmount = 4800798;
  int amountApproach = 13;
  int apartmentsInApproach = 50;
  int result = totalAmount / (amountApproach * apartmentsInApproach);

  std::cout << "Приветствуем вас в калькуляторе квартплаты!\n";
  std::cout << "Введите сумму, указанную в квитанции: " << totalAmount << " руб.\n";
  std::cout << "Сколько подъездов в вашем доме? " << amountApproach << "\n";
  std::cout << "Сколько квартир в каждом подъезде? " << apartmentsInApproach << "\n";
  std::cout << "-----Считаем-----\n";
  std::cout << "Каждая квартира должна платить по " << result << " руб.";
    }
