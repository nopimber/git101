# สารบัญเนื้อหาสรุป
## Reference Pointer
### & (ampersand)
> & อยู่หน้าตัวแปรไหนจะไปเอา address ของตัวแปรนั้นมา
### Example
```
int main(){
    int x = 100;
    printf("value of x is %d\n", x);
    printf("reference of x is %lu\n", &x);
    printf("reference of x is hexadecimal is %p\n", &x); 
    // %p เป็นการ print ตัวเลขจำนวนเต็มแต่เป็นตัวเลขจำนวนเต็มที่เป็นเลขฐาน 16
}
```

