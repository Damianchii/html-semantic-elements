
# 🚀 HTML Elementy Semantyczne
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html" />
  </a>
</p>

### Semantyczne Elementy - sama nazwa znacznika zdradza co może znajdzować się wewnątrz tego znacznika

## ➡️ `<header>` - Nagłówek
#### <b>Nagłówek strony</b> - zazwyczaj wewnątrz znajduję się nawigacja 
```bash
  <header>
        <nav>
          ...
        </nav>
  </header>
```
## ➡️ `<nav>` - Navigacja/menu
```bash
  <nav>
       <!-- Nawigacja/menu strony - zazwyczaj wewnątrz znajduję się nawigacja -->
       <ul>
          <li>...</li>
          <li>...</li>
       </ul>
  </nav>
```
## ➡️ `<main>` - Główna treść witryny
```bash
  <main>
        <!-- Główna część strony - zawartość głowna -->
        <main>
          <article>
            ...
          </article>
        </main>
  </main>
```
## ➡️ `<article>` - Artykuł
```bash
  <nav>
      <!-- Artykuł - zazwyczaj autonomiczny fragment strony - inaczaj mówiąć, możemy wziąć ten   element i wrzucić go na inna strone, będą to elementy typu post na bogu. Bardzo ważny dla przeglądarek -->
      <article>
        <p>
          ...
        </p>
      </article>
  </nav>
```
## ➡️ `<aside>` - Boczne menu
```bash
  <nav>
      <!-- Boczne menu - treść mało powiązana z głowną zawartościa storny , reklamy , opcje itd. Element ten zazwyczaj jest wielokrotnie powtarzany w każdej podstronie-->
       <ul>
          <li><a href="#">...</a></li>
          <li><a href="#">...</a></li>
       </ul>
  </nav>
```
## ➡️ `<footer>` - Stopka
```bash
  <nav>
      <!-- Stopka strony - Zazwyczaj wewnątrz znajduja sie dane firmy itd -->
      &copy; expample@strona.wwww
  </nav>
```

## ➡️ `<section>` - sekcja
```bash
      <!-- Sekcja - Grupuje tematyczne treść o określonym znaczeniu, często łączy sie z article np. zgrupuje sekcje komentarzy gdzie każdy komentarz to article -->
      <section>
        <article>...</article>
        <article>...</article>
        <article>...</article>
      </section>
```
