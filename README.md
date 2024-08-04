
# 🚀 HTML Elementy Semantyczne
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html" />
  </a>
</p>

### Semantyczne Elementy - sama nazwa znacznika zdradza co może znajdzować się wewnątrz tego znacznika

## ➡️ `<header>` - Nagłówek
#### Nagłówek strony - zazwyczaj wewnątrz znajduję się nawigacja 
```bash
  <header>
        <nav>
          ...
        </nav>
  </header>
```
## ➡️ `<nav>` - Navigacja/menu
#### Nawigacja/menu strony - zazwyczaj wewnątrz znajduję się nawigacja
```bash
  <nav>
       <ul>
          <li>...</li>
          <li>...</li>
       </ul>
  </nav>
```
## ➡️ `<main>` - Główna treść witryny
#### Główna część strony - zawartość głowna 
```bash
  <main>
        <main>
          <article>
            ...
          </article>
        </main>
  </main>
```
## ➡️ `<article>` - Artykuł
#### Artykuł - zazwyczaj autonomiczny fragment strony - inaczaj mówiąć, możemy wziąć ten   element i wrzucić go na inna strone, będą to elementy typu post na bogu. Bardzo ważny dla przeglądarek
```bash
  <nav>
      <article>
        <p>
          ...
        </p>
      </article>
  </nav>
```
## ➡️ `<aside>` - Boczne menu
#### Boczne menu - treść mało powiązana z głowną zawartościa storny , reklamy , opcje itd. Element ten zazwyczaj jest wielokrotnie powtarzany w każdej podstronie
```bash
  <nav>
       <ul>
          <li><a href="#">...</a></li>
          <li><a href="#">...</a></li>
       </ul>
  </nav>
```
## ➡️ `<footer>` - Stopka
#### Stopka strony - Zazwyczaj wewnątrz znajduja sie dane firmy itd
```bash
  <nav>
      &copy; expample@strona.wwww
  </nav>
```

## ➡️ `<section>` - sekcja
#### Sekcja - Grupuje tematyczne treść o określonym znaczeniu, często łączy sie z article np. zgrupuje sekcje komentarzy gdzie każdy komentarz to article
```bash
      <section>
        <article>...</article>
        <article>...</article>
        <article>...</article>
      </section>
```
