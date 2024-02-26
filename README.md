# SEMAFORO
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(13, LOW);//AMARELO 1 
  digitalWrite(11, HIGH);//VERDE 1
  digitalWrite(12, LOW);//VERMELHO 1 
  digitalWrite(9, LOW);//AMARELO 2 
  digitalWrite(8, LOW);//VERDE 2
  digitalWrite(10, HIGH);//VERMELHO 2
  delay(3000); 
  
  digitalWrite(13, HIGH);//AMARELO 1
  digitalWrite(11, LOW);//VERDE 1
  digitalWrite(12, LOW);//VERMELHO 1
  digitalWrite(9, LOW);//AMARELO 2 
  digitalWrite(8, LOW);//VERDE 2
  digitalWrite(10, HIGH);//VERMELHO 2
  delay(1500);
  
  digitalWrite(13, LOW);//AMARELO 1
  digitalWrite(11, LOW);//VERDE 1
  digitalWrite(12, HIGH);//VERMELHO 1 
  digitalWrite(9, LOW);//AMARELO 2 
  digitalWrite(8, HIGH);//VERDE 2
  digitalWrite(10, LOW);//VERMELHO 2
  delay(3000);
  
  digitalWrite(13, LOW);//AMARELO 1
  digitalWrite(11, LOW);//VERDE 1
  digitalWrite(12, HIGH);//VERMELHO 1 
  digitalWrite(9, HIGH);//AMARELO 2 
  digitalWrite(8, LOW);//VERDE 2
  digitalWrite(10, LOW);//VERMELHO 2
  delay(1500);
}
