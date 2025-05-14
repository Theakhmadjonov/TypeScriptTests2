# NestJS Guard, Interceptor va Pipes Test Savollari

### 1. NestJS guardlar qaysi metod orqali ishlaydi?

A) `canActivate()`

### 2. Guards qaysi interfaceni implement qilishi kerak?

D) `CanActivate`

### 3. NestJS interceptorlar qaysi patternni qo'llaydi?

D) Aspect-Oriented Programming (AOP) pattern

### 4. Interceptorlar qaysi interfaceni implement qilishi kerak?

B) `NestInterceptor`

### 5. NestJS-da Pipe-larning asosiy vazifasi nima?

C) Ma'lumotlarni validatsiya va transformatsiya qilish

### 6. Guard-dan qaytariladigan `false` qiymati nimani anglatadi?

B) So'rov `403 Forbidden` xatosi bilan rad etiladi

### 7. Interceptor-dagi `intercept()` metodi qaysi parametrlarni qabul qiladi?

A) `(context, next)`

### 8. Pipe-lar qaysi interfaceni implement qilishi kerak?

B) `PipeTransform`

### 9. NestJS-da Guard-ni global darajada qo'llash uchun qaysi koddan foydalaniladi?

A) `app.useGlobalGuards(new RolesGuard())`

### 10. Global Interceptor qanday e'lon qilinadi?

C) `app.useGlobalInterceptors(new LoggingInterceptor())`

### 11. Global darajada Pipe-ni qanday qo'llash mumkin?

A) `app.useGlobalPipes(new ValidationPipe())`

### 12. Custom guardni qaysi decorator orqali controller yoki method darajasida qo'llash mumkin?

C) `@UseGuards()`

### 13. Interceptor-dan request va response-ni o'zgartirish uchun qaysi RxJS operatoridan foydalanish mumkin?

B) `map()`

### 14. NestJS-da qaysi built-in Pipe mavjud emas?

C) `TransformPipe`

### 15. `ParseIntPipe` qanday vazifani bajaradi?

B) String qiymatni butun songa aylantiradi va tekshiradi
