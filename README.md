# project_class_diagram
#include<iostream>


class Automobile                       //автомобили
{
 protected:
 int wheels=4,
    lights=4;
};

class PassengerCar: public Automobile   //легковые
{
 private:
 int passenger=5;   //2 спереди 3 сзади
};

class FreightCar: public Automobile    //грузовые
{
 public:
  void embarcation ();                //функция погрузки
  private:
  MinCarrying=1000;                   //минимальная грузоподъёмност 1000кг
};

class FordCar: public PassengerCar 
{
};

class VAZ: public PassengerCar
{
};
