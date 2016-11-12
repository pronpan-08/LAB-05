พรพรรณ  เกิดรัตน์  57030201


#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
  
  เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงคำ ว่า This is text 1.
 บรรทัดที่2 แสดงคำ ว่า This is text 2. บรรทัดถัดที่3 แสดงคำ ว่า This is text 3. 
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-1.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>
 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้
 
 
เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงคำ 3 and 6

 
 ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-2.png?raw=true)





###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร


ตอบ {} เป็นตัวเก็บเลขตัวข้างหลังตาลำดับ เช่นดังการทดลอง Console.WriteLine(" {0} and {1}.",3,6);  

{0} จะเป็นตำแหน่งของ 3  {1} จะเป็นตำแหน่งของ 6  
<hr>
<hr>
<hr>
<hr>
<hr>
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย

ตอบ ใช้ได้ หาก Console.WriteLine(" {0} and {2} and {3}.",3,6,5,8);  

หากมีข้อมูลที่ตำแหน่งนั้นครบ คือ 8คือตำแหน่งที่ {3} แต่ถ้า Console.WriteLine(" {0} and {2} and {3}.",3,6,5);  

ไม่มีข้อมูลในตำแหน่ง{3} จะรันโปรแกรมไม่ได้
<hr>
<hr>
<hr>
<hr>
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
 
 เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงคำ ว่า  6 and 3 and 6
  
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-3.png?raw=true)

<hr>
<hr>
<hr>
<hr>
<hr>

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
  
  เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงดังรูป
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-4.png?raw=true)
  
<hr>
<hr>
<hr>
<hr>
<hr>

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร


ตอบ Console.WriteLine("{x,y}",1);  x คือตำแหน่งข้อมูลที่ต้องการให้ปรากฎ y คือตำแหน่งความกว้างของอาร์กิวเมนส์
เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงดังรูป

<hr>
<hr>
<hr>
<hr>
<hr>


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
  
  เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงดังรูป
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-5.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
  
  เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงดังรูป
  
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-6.png?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  เมื่อทำการรันโปรแกรม จะปรากฎ หน้า command line หรือหน้าต่างสีดำ แสดงดังรูป
  
  ![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-7.png?raw=true)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```


1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
       
       ผลลัพธ์จะเป็นไปตามตัวเลขหน้าคำสั่ง จนมาถึงคำสั่งที่ 14 จะเป็ฯตาราง value squared และ cubed
       
 15          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
 
 16   Console.WriteLine("{0:#.###}.", 1234.56789);
 
       พอจบตารางก็จะเป็ฯของ 15และ16ตาลำดับ
       

![](https://github.com/pronpan-08/LAB-05/blob/master/img/lab5-8.png?raw=true)
