# Втора лабораториска вежба по Софтверско инженерство

## Леона Волканоска, бр. на индекс 213017

### Control Flow Graph

![finalfinalsilab](https://github.com/LeonaVolkanoska/SI_2023_lab2_213017/assets/61162225/77963100-47d0-498a-8025-0a8ad0707d5b)

### Цикломатска комплексност
Цикломатската комплексност на овој код е 11, истата ја добив на два начини: 
1. преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=10.
2. E - N + 2 каде E претставува бројот на ребра=35, N претставува бројот на јазли=22.

### Тест случаеви според критериумот Every statement

![prvatabela](https://github.com/LeonaVolkanoska/SI_2023_lab2_213017/assets/61162225/4a4af0b5-3e2d-404e-8b6c-fd534897a90d)

За да ги изминам сите ребра (Every Branch) ги користам следните услови:
- (user != null) && (password != null) && (mail != null) И (user == null) || (password == null) || (mail == null)
- email да содржи "@" и "." и email да не содржи "@" и "."
- allUsers list да е празна и allUsers list да не е празна
- еxistingUSer != email и existingUser == email
- username == null

### Тест случаеви според критериумот Every Path

![tabela2](https://github.com/LeonaVolkanoska/SI_2023_lab2_213017/assets/61162225/1443781a-e66a-42cc-af49-cf6179851f3e)

Потребни тест случаеви за Multiple Condition if (user==null || user.getPassword()==null || user.getEmail()==null) се:
- (user != null) && (password != null) && (mail != null)
- (user == null)
- (password == null)
- (mail == null)
