#include <stdio.h>
#include <string.h> // Thu vien cung cap cac keyword lien quan den string

int main(){
    char str1[6] = "12345"; // Do dai string = 6 thi chua duoc 5 ki tu, vi ky tu thu 6 la khoa an de ket thuc string
    char str2[20] = "54321";
    char str3[20];

    strcpy(str1, str2); // Sao chep str2 vao str1
    printf("Strcpy str1: %s\n",str1);
    printf("Strcpy str2: %s\n\n",str2);
    
    strcpy(str3,str1);
    strcat(str1,str2); // Ghep str2 vao str1
    printf("strcat str1: %s\n",str1);
    printf("strcat str2: %s\n\n",str2);

    strlen(str1);
    printf("Strlen = %d\n",strlen(str1)); // Dem do dai cua string (bao gom ca dau cach)
    printf("Strlen = %d\n",strlen(str3));

    printf("Strcmp = %d\n",strcmp(str3, str2)); // So sanh do dai 2 string theo tung ky tu tu trai qua phai, tra ve cac ket qua: -1, 0, 1
    // str1 > str2 = 1; str1 == str2 = 0; str1 < str2 = -1;

    printf("strchr = %s\n", strchr(str1, '3')); // Tim ky tu '3' trong str1, tu trai qua phai, sau do cat bo cac ky tu phia truoc den '3'
    // Khong the tim va cat duoc '3' o vi tri thu 2

    printf("strstr = %s\n", strstr(str1,"43")); // Tim va cat cac ky tu phia truoc den '34' dau tien tim thay. Khong tim thay se ra 'null'.
}
