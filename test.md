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

A) Requestni filtrlash
B) Response-ni transformatsiya qilish
C) Ma'lumotlarni validatsiya va transformatsiya qilish
D) Ma'lumotlarni shifrlash va deshifrlash

### 6. Guard-dan qaytariladigan `false` qiymati nimani anglatadi?

A) So'rov muvaffaqiyatli bajarildi
B) So'rov `403 Forbidden` xatosi bilan rad etiladi
C) Guard keyingi middleware-ga o'tkaziladi
D) So'rov `401 Unauthorized` xatosi bilan rad etiladi

### 7. Interceptor-dagi `intercept()` metodi qaysi parametrlarni qabul qiladi?

A) `(context, next)`
B) `(request, response, next)`
C) `(context, callback)`
D) `(req, res, next)`

### 8. Pipe-lar qaysi interfaceni implement qilishi kerak?

A) `NestPipe`
B) `PipeTransform`
C) `Transform`
D) `ValidationPipe`

### 9. NestJS-da Guard-ni global darajada qo'llash uchun qaysi koddan foydalaniladi?

A) `app.useGlobalGuards(new RolesGuard())`
B) `app.useGlobal(new RolesGuard())`
C) `app.useGuard(new RolesGuard())`
D) `app.applyGuard(new RolesGuard())`

### 10. Global Interceptor qanday e'lon qilinadi?

A) `app.addGlobalInterceptor(new LoggingInterceptor())`
B) `app.useInterceptor(new LoggingInterceptor())`
C) `app.useGlobalInterceptors(new LoggingInterceptor())`
D) `app.setInterceptor(new LoggingInterceptor())`

### 11. Global darajada Pipe-ni qanday qo'llash mumkin?

A) `app.useGlobalPipes(new ValidationPipe())`
B) `app.usePipe(new ValidationPipe())`
C) `app.setGlobalPipe(new ValidationPipe())`
D) `app.applyPipe(new ValidationPipe())`

### 12. Custom guardni qaysi decorator orqali controller yoki method darajasida qo'llash mumkin?

A) `@ApplyGuard()`
B) `@Guard()`
C) `@UseGuards()`
D) `@WithGuard()`

### 13. Interceptor-dan request va response-ni o'zgartirish uchun qaysi RxJS operatoridan foydalanish mumkin?

A) `switchMap()`
B) `map()`
C) `tap()`
D) `flatMap()`

### 14. NestJS-da qaysi built-in Pipe mavjud emas?

A) `ValidationPipe`
B) `ParseIntPipe`
C) `TransformPipe`
D) `ParseArrayPipe`

### 15. `ParseIntPipe` qanday vazifani bajaradi?

A) Faqat butun son kiritilishini tekshiradi
B) String qiymatni butun songa aylantiradi va tekshiradi
C) Arrayni butun sonlarga aylantiradi
D) Faqat musbat butun sonlar kiritilishini tekshiradi
