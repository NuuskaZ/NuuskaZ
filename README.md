```


int led1 = D0;
int led2 = D2;
int led3 = D4;
int led4 = D7;

void setup() {

  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
  pinMode(led4, OUTPUT);

}

void loop() {
   digitalWrite(led1, HIGH);
   digitalWrite(led2, LOW);
   digitalWrite(led3, LOW);
   digitalWrite(led4, LOW);
  delay(500);

   digitalWrite(led1, LOW);
   digitalWrite(led2, HIGH);
   digitalWrite(led3, LOW);
   digitalWrite(led4, LOW);
  delay(500);
  
   digitalWrite(led1, LOW);
   digitalWrite(led2, LOW);
   digitalWrite(led3, HIGH);
   digitalWrite(led4, LOW);
  delay(500);
 
   digitalWrite(led1, LOW);
   digitalWrite(led2, LOW);
   digitalWrite(led3, LOW);
   digitalWrite(led4, HIGH);
  delay(500); 
  }
  ![Leipälauta](https://user-images.githubusercontent.com/91258023/134660456-c4779746-9f0e-4905-b4c3-d7ccd5400684.jpg)

 
```
