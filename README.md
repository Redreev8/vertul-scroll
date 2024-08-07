# Vertul scroll

## Props
```
slider: HTMLElement ,
classSlide: string,
classSlider: {
  [key: number]: string
},
textSlider: {
  [key: number]: string
},
box: HTMLElement,
list: any[],
heightRow: number,
gap: number,
colums: number,
active: number,
classList: {
  ul: string,
  li: string
}
```

- box класс влоденый в slider HTML элементов
- list массив элементов
- gap растояние между элементами
- heightRow высота элемента
- colums колическтво колонок
- active активированый индех элемента при первом запуске
- classList классы тегов ul и li defult:
```
{
  ul: 'number-list',
  li: 'number-list__item',
}
```
