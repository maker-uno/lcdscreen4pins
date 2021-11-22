#include <LiquidCrystal_I2C_AvrI2C.h>

LiquidCrystal_I2C_AvrI2C lcd(0x3F,16,2);
 
void setup()
{
  lcd.begin();
  lcd.backlight();
  lcd.setCursor(0,0);
  lcd.print("Hello my follower"); //İlk satıra yazalım
  lcd.setCursor(0,1);
  lcd.print("Use for good day"); //İkinci satıra yazalım
}
 
void loop()
{
} 
