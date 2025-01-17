# React Todo App

Lihtne Todo rakendus, mis on loodud kasutades React'i ja Shadcn/ui komponente.

## Funktsionaalsused

- Todo elementide kuvamine
- Uute todo elementide lisamine
- Todo elementide märkimine tehtuks
- Todo elementide kustutamine

## Tehnoloogiad

- React
- Tailwind CSS
- Shadcn/ui komponendid
- Lucide ikoonid

## Paigaldamine

1. Klooni repositoorium:
```bash
git clone https://github.com/lembitlindau/react-todo-app.git
```

2. Liigu projekti kausta:
```bash
cd react-todo-app
```

3. Installi sõltuvused:
```bash
npm install
```

4. Installi vajalikud shadcn/ui komponendid:
```bash
npx shadcn-ui@latest add card button input checkbox
```

5. Käivita arendusserver:
```bash
npm run dev
```

6. Ava brauseris [http://localhost:5173](http://localhost:5173)

## Projekti struktuur

```
src/
  ├── components/
  │   └── TodoApp.jsx    # Peamine Todo rakenduse komponent
  ├── App.jsx            # Root komponent
  └── main.jsx          # Rakenduse sisendpunkt
```

## Kasutamine

- Uue ülesande lisamiseks sisesta tekst ülemisse sisendvälja ja vajuta "Lisa" nuppu
- Ülesande märkimiseks tehtuks klõpsa märkeruudul
- Ülesande kustutamiseks vajuta prügikasti ikoonile

## Litsents

MIT