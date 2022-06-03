# Task-11.1PCDH-Project-code


int led1 = A5; 

int led2 = D7; 
int phototransistor = A0;
int analogValue;


void setup() {

  

  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(phototransistor,INPUT);

}


void loop() {
 

analogValue = analogRead(phototransistor);

if(analogValue>14){
    digitalWrite(led1,LOW);
    digitalWrite(led2,LOW);
}else{
    digitalWrite(led1,HIGH);
    digitalWrite(led2,HIGH);
}

 
}

