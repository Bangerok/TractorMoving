<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h1>
        <a href="https://funprojectsforsoul.github.io/TractorMoving/">TractorMoving</a>
    </h1>
</div>

<div align="center">
    <a href="https://github.com/FunProjectsForSoul/TractorMoving/blob/master/docs/README.md">
        <img alt="english-version" src="https://raw.githubusercontent.com/FunProjectsForSoul/TractorMoving/master/assets/languages/english.png"/>
    </a>
</div>

<div align="center">
    <img src="https://img.shields.io/github/last-commit/FunProjectsForSoul/TractorMoving" height="25" alt="last-commit" />
    <img src="https://img.shields.io/github/v/release/FunProjectsForSoul/TractorMoving" height="25" alt="last-release" />
    <img src="https://tokei.rs/b1/github/FunProjectsForSoul/TractorMoving?category=code" height="25" alt="code-lines" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=FunProjectsForSoul_TractorMoving&metric=bugs" height="25" alt="sonar-cloud-bugs" />
    <img src="https://github.com/FunProjectsForSoul/TractorMoving/actions/workflows/check-style.yml/badge.svg" height="25" alt="checking-style" />
    <img src="https://github.com/FunProjectsForSoul/TractorMoving/actions/workflows/sonar.yml/badge.svg" height="25" alt="checking-sonar" />
    <img src="https://github.com/FunProjectsForSoul/TractorMoving/actions/workflows/build.yml/badge.svg" height="25" alt="build" />
</div>

### 📖 Описание
___

Есть квадратное поле размером **n × n** ячеек. В центре этого поля находится квадратная гора размером **м × м** клеток,
а в нижнем левом углу — квадратный трактор **k × k** ячеек, который может передвигаться по полю.

### ⛓ Условия
___

1. Размеры: поле — n, гора — m и трактор — k, вводятся с клавиатуры;
2. Трактор перемещается на произвольное количество ячеек вверх, вниз, влево или вправо;
_Если нет возможности передвинуть трактор (например, если путь упирается в гору), то он не начнет движение и останется 
на месте. Поле считается замкнутым, то есть когда трактор выезжает за левую границу поля — появляется справа и т. д_;
3. Отображение текущих координат левого нижнего угла трактора.

### ❗ Требования
___

* **JDK**: 16 и выше;

### 📋 Инструкция по запуску
___

*Все команды выполняются в консоли.*
1. Создать папку: `mkdir GitProjects`;
2. Перейти в нее: `cd GitProjects`;
3. Клонировать код репозитория: `git clone https://github.com/FunProjectsForSoul/TractorMoving.git`;
4. Перейти в созданную папку: `cd TractorMoving`;
5. Собрать проект: `mvn clean install`;
6. После выполнения 5 пункта — будет создана папка с именем **“target”**. Переходим в нее: `go target`;
7. Внутри будет находиться файл **“tractor-1.0.0.jar”**.
Запускаем его командой: `java -jar tractor-1.0.0.jar`;
8. Запустится консольное приложение **(см. "Консольный интерфейс")**.

```java
public class TractorApplication {
  
   public static void main(String[] args) {
      run();
   }
   
   // ... остальные методы
}
```

### 💻 Интерфейс приложения
___
<div align="center">
   <img style="border: solid #465241;" src="https://raw.githubusercontent.com/FunProjectsForSoul/TractorMoving/master/assets/tractor-moving.gif" alt="gui-interface" />
</div>

### 🎫 Лицензия
___

**[Creative Commons Legal Code](https://github.com/Bangerok/TractorMoving/blob/master/LICENSE)**

_Copyright ©2021, Vladislav [[Bangerok]](https://github.com/Bangerok) Kuznetsov_