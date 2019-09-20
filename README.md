int ledPins[] = {9,8,7,6,5,4};

void setup() {
  // put your setup code here, to run once:
  int index;

   for(index = 0; index <= 5; index++)
  {
    pinMode(ledPins[index],OUTPUT);
  }
}

void loop() {
  // put your main code here, to run repeatedly:
    int index;
  int delayTime = 100; 
  
  for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[1], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
    digitalWrite(ledPins[4], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[5], LOW);
     }
    delay(100);
     for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
    digitalWrite(ledPins[1], HIGH);
    digitalWrite(ledPins[4], HIGH);
    delay(450);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
     }
    delay(100);
     for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
    digitalWrite(ledPins[1], HIGH);
    digitalWrite(ledPins[4], HIGH);
    delay(450);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
     }
    delay(100);
     for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[4], HIGH);
    digitalWrite(ledPins[1], HIGH);
    delay(450);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
     }
    delay(100);
     for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
  
  for(index = 0; index <= 5; index++)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(250);                    // pause to slow down
  }
    for(index = 0; index <= 5; index++)
    {
      digitalWrite(ledPins[index], LOW);
      delay(250);
    }
      for(index = 0; index <= 5; index++)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(250);                    // pause to slow down
  }
    for(index = 0; index <= 5; index++)
    {
      digitalWrite(ledPins[index], LOW);
      delay(250);
    }
    for(index = 0; index <= 5; index++)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(250);                    // pause to slow down
  }
    for(index = 0; index <= 5; index++)
    {
      digitalWrite(ledPins[index], LOW);
      delay(250);
    }
    for(index = 0; index <= 5; index++)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(250);                    // pause to slow down
  }
  delay(300);
  for(index = 0; index <=5; index++)
  {
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[1], LOW);
   digitalWrite(ledPins[2], LOW);
   digitalWrite(ledPins[3], LOW);
   digitalWrite(ledPins[4], LOW);
   digitalWrite(ledPins[5], LOW);
   digitalWrite(ledPins[6], LOW);
   delay(150);
  }
  for(index = 0; index <=5; index++)
{
  digitalWrite(ledPins[0], HIGH);
  digitalWrite(ledPins[1], HIGH);
  digitalWrite(ledPins[2], HIGH);
  digitalWrite(ledPins[3], HIGH);
  digitalWrite(ledPins[4], HIGH);
  digitalWrite(ledPins[5], HIGH);
   delay(200);
}
 
  for(index = 0; index <=5; index++)
  {
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[1], LOW);
   digitalWrite(ledPins[2], LOW);
   digitalWrite(ledPins[3], LOW);
   digitalWrite(ledPins[4], LOW);
   digitalWrite(ledPins[5], LOW);
   digitalWrite(ledPins[6], LOW);
  }

  for(index = 0; index <=5; index++)
 {
  digitalWrite(ledPins[0], HIGH);
  digitalWrite(ledPins[2], HIGH);
  digitalWrite(ledPins[4], HIGH);
  delay(50);
 }
  for(index = 0; index <=5; index++)
 {
  digitalWrite(ledPins[0], LOW);
  digitalWrite(ledPins[4], LOW);
  digitalWrite(ledPins[2], LOW);
  delay(50);
 }

  

  // Step through the first four LEDs
  // (We'll light up one in the lower 3 and one in the upper 3)

  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
   for(index = 0; index <= 5; index++)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(delayTime);                    // pause to slow down
    digitalWrite(ledPins[index], LOW);   // turn LED off
  }

  // step through the LEDs, from 5 to 0

  for(index = 5; index >= 0; index--)
  {
    digitalWrite(ledPins[index], HIGH);  // turn LED on
    delay(100);                    // pause to slow down
    digitalWrite(ledPins[index], LOW);   // turn LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
      for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
      for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
   for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
      for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
       for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <=5; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+1], HIGH);  // Skip four, and turn that LED on
    delay(100);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+1], LOW);   // Skip four, and turn that LED off
  }
    for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[1], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
    digitalWrite(ledPins[4], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[5], LOW);
     }
    delay(100);
    
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
   for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
    digitalWrite(ledPins[1], HIGH);
    digitalWrite(ledPins[4], HIGH);
    delay(450);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
     }
    delay(100);

    for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }

for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
    digitalWrite(ledPins[1], HIGH);
    digitalWrite(ledPins[4], HIGH);
    delay(450);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
     }
    delay(100);

        for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 0; index++) 
  {
    digitalWrite(ledPins[4], HIGH);
    digitalWrite(ledPins[1], HIGH);
    delay(450);
    digitalWrite(ledPins[4], LOW);
    digitalWrite(ledPins[1], LOW);
    digitalWrite(ledPins[0], HIGH);
    digitalWrite(ledPins[5], HIGH);
    delay(450);
    digitalWrite(ledPins[0], LOW);
    digitalWrite(ledPins[5], LOW);
    digitalWrite(ledPins[2], HIGH);
    digitalWrite(ledPins[3], HIGH);
    delay(450);
    digitalWrite(ledPins[2], LOW);
    digitalWrite(ledPins[3], LOW);
     }
    delay(100);
        for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }
  for(index = 0; index <= 2; index++) // Step from 0 to 3
  {
    digitalWrite(ledPins[index], HIGH);    // Turn a LED on
    digitalWrite(ledPins[index+3], HIGH);  // Skip four, and turn that LED on
    delay(200);                      // Pause to slow down the sequence
    digitalWrite(ledPins[index], LOW);     // Turn the LED off
    digitalWrite(ledPins[index+3], LOW);   // Skip four, and turn that LED off
  }

    
  
  
  
}

