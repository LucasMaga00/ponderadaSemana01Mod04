Para ir para a parte 2, [clique aqui](https://www.tinkercad.com/things/47e8BnMeeov-arduino-ponderada-01-parte-02/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits&sharecode=xMwQM4Or4RUrgSFtedhvtV1SiGLxZI_e7r6639hMliw)

O código que utilizei para realizar a atividade, foi o seguinte:

```cpp
int led = 10;
  
void setup()
{
  pinMode(led, OUTPUT);
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(led, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```