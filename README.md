# ԵՊՀ բակալավրի տիտղոսաթերթի ձևանմուշ  
# Шаблон бакалаврской выпускной работы ЕГУ  
# YSU Bachelor Thesis Template

---

## Հայերեն

Սա ԵՊՀ ուսանողների համար նախատեսված բակալավրի ավարտական աշխատանքի ոչ պաշտոնական ձևանմուշ է։

Ռուսերեն և անգլերեն տարբերակները տրված են ներքևում։

Ձևանմուշը ներառում է՝

- LaTeX / Overleaf տարբերակ
- DOCX տարբերակ
- A4 էջի կարգավորում
- Պահանջվող լուսանցքներ
- Հայերեն Unicode տառատեսակի կարգավորում
- Տիտղոսաթերթի ձևանմուշ
- Ստորագրությունների / պաշտպանության թույլտվության էջի ձևանմուշ

### Ձևաչափման հիմնական կարգավորումներ

Ձևանմուշը կառուցված է հետևյալ պահանջների հիման վրա՝

- Թղթի չափս՝ A4
- Լուսանցքներ՝
  - ձախից՝ 3.0 սմ
  - աջից՝ 1.5 սմ
  - վերևից՝ 2.0 սմ
  - ներքևից՝ 2.5 սմ
- Հիմնական տեքստի տառաչափ՝ 12 pt
- Միջտողային հեռավորություն՝ 1.5
- Պարբերության խորք՝ 1 սմ
- Էջերի համարակալում՝ ներքևում, կենտրոնում
- Յուրաքանչյուր գլուխ սկսվում է նոր էջից
- Գլուխների վերնագրերը գրվում են թավ և գլխատառերով

### Տառատեսակներ

LaTeX տարբերակում անհրաժեշտ է, որ հայերեն տառատեսակների ֆայլերը տեղադրվեն հետևյալ թղթապանակում՝

```text
Font/
```

Սպասվող ֆայլերի անուններն են՝

```text
GHEAGrpalatReg.otf
GHEAGpalatBld.otf
GHEAGrapalatRit.otf
GHEAGrapalatBlit.otf
```

Տառատեսակների ֆայլերը ներառված չեն այս պահոցում։ Օգտատերերը պետք է դրանք ավելացնեն ձեռքով, եթե ունեն դրանց օգտագործման իրավունք։

### Overleaf-ում օգտագործելու եղանակը

1. Ստեղծեք նոր նախագիծ Overleaf-ում։
2. Վերբեռնեք `main.tex` ֆայլը։
3. Ստեղծեք `Font` անունով թղթապանակ։
4. Վերբեռնեք պահանջվող `.otf` տառատեսակների ֆայլերը `Font` թղթապանակի մեջ։
5. Compiler-ը ընտրեք **XeLaTeX**։

### DOCX տարբերակ

DOCX ֆայլը տրամադրված է որպես ձևանմուշի խմբագրվող Microsoft Word տարբերակ։

### Նշում

Սա ուսանողի կողմից պատրաստված ոչ պաշտոնական ձևանմուշ է։ Մինչև աշխատանքի վերջնական հանձնումը անպայման ստուգեք ձևաչափման պահանջները ձեր ամբիոնի, ֆակուլտետի կամ ղեկավարի հետ։

---

## Русский

Это неофициальный шаблон бакалаврской выпускной работы для студентов Ереванского государственного университета.

Армянская версия находится выше, английская версия находится ниже.

Шаблон включает:

- версию LaTeX / Overleaf
- версию DOCX
- настройку страницы A4
- необходимые поля страницы
- настройку армянского Unicode-шрифта
- шаблон титульного листа
- шаблон страницы с подписями / допуском к защите

### Основные параметры форматирования

Шаблон подготовлен на основе следующих требований:

- Размер бумаги: A4
- Поля:
  - слева: 3.0 см
  - справа: 1.5 см
  - сверху: 2.0 см
  - снизу: 2.5 см
- Размер основного текста: 12 pt
- Межстрочный интервал: 1.5
- Абзацный отступ: 1 см
- Нумерация страниц: внизу по центру
- Каждая глава начинается с новой страницы
- Названия глав пишутся полужирным шрифтом и заглавными буквами

### Шрифты

LaTeX-версия ожидает, что необходимые армянские шрифты будут помещены в папку:

```text
Font/
```

Ожидаемые имена файлов:

```text
GHEAGrpalatReg.otf
GHEAGpalatBld.otf
GHEAGrapalatRit.otf
GHEAGrapalatBlit.otf
```

Файлы шрифтов не включены в этот репозиторий. Пользователи должны добавить их вручную, если имеют право на их использование.

### Использование в Overleaf

1. Создайте новый проект в Overleaf.
2. Загрузите файл `main.tex`.
3. Создайте папку с названием `Font`.
4. Загрузите необходимые `.otf` файлы шрифтов в папку `Font`.
5. Выберите compiler **XeLaTeX**.

### DOCX версия

DOCX-файл предоставлен как редактируемая версия шаблона для Microsoft Word.

### Примечание

Это неофициальный студенческий шаблон. Перед финальной сдачей обязательно проверьте требования к оформлению у вашей кафедры, факультета или научного руководителя.

---

## English

This repository contains an unofficial reusable bachelor thesis template for students of Yerevan State University.

For Armenian and Russian versions, see above.

The template includes:

- LaTeX / Overleaf version
- DOCX version
- A4 page setup
- Required margins
- Armenian Unicode font setup
- Title page template
- Signature / approval page template

### Formatting

The template follows the basic formatting requirements:

- Paper size: A4
- Margins:
  - Left: 3.0 cm
  - Right: 1.5 cm
  - Top: 2.0 cm
  - Bottom: 2.5 cm
- Main text font size: 12 pt
- Line spacing: 1.5
- Paragraph indent: 1 cm
- Page numbers: bottom center
- Chapters start on a new page
- Chapter titles are bold and uppercase

### Fonts

The LaTeX version expects the required Armenian font files to be placed inside a folder named:

```text
Font/
```

Expected filenames:

```text
GHEAGrpalatReg.otf
GHEAGpalatBld.otf
GHEAGrapalatRit.otf
GHEAGrapalatBlit.otf
```

The font files are not included in this repository. Users should add them manually if they have the right to use them.

### Overleaf Usage

1. Create a new Overleaf project.
2. Upload `main.tex`.
3. Create a folder named `Font`.
4. Upload the required `.otf` font files into the `Font` folder.
5. Set the compiler to **XeLaTeX**.

### DOCX Usage

The DOCX file is provided as an editable Microsoft Word version of the same template.

### Notes

This is an unofficial student-made template. Always check the final formatting requirements with your department, faculty, or supervisor before submission.
