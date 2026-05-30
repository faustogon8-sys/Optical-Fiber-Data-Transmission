int ENA = 9; 
int ENB = 10; 
// Dirección motores 
int IN1 = 7; 
int IN2 = 6; 
int IN3 = 5; 
int IN4 = 4; 
int valoresPWM[] = {25, 76, 128, 178, 230, 255}; // 10%,30%,50%,70%,90%,100% 
int i = 0; 
 
void setup() { 
  pinMode(ENA, OUTPUT); 
  pinMode(ENB, OUTPUT); 
 
  pinMode(IN1, OUTPUT); 
  pinMode(IN2, OUTPUT); 
  pinMode(IN3, OUTPUT); 
  pinMode(IN4, OUTPUT); 
 
  // Mismo sentido 
  digitalWrite(IN1, HIGH); 
  digitalWrite(IN2, LOW); 
 
  digitalWrite(IN3, HIGH); 
  digitalWrite(IN4, LOW); 
} 
 
void loop() { 
 
  // MISMO PWM en ambos 
  analogWrite(ENA, valoresPWM[i]); 
  analogWrite(ENB, valoresPWM[i]); 
 
  delay(3000); 
 
  i++; 
  if (i > 5) { 
    i = 0; 
  } 
}
