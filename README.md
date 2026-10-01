# Node.js CI/CD Lab

## Жоба туралы

Бұл жоба «DevOps-тың қолданбалы аспектілері» пәні бойынша СОӨЖ жұмысы үшін әзірленді.

Жоба Node.js негізінде жасалған қарапайым Calculator қосымшасын қамтиды.

Қосымша келесі операцияларды орындайды:

- қосу;
- азайту;
- көбейту.

## Қолданылған технологиялар

- Node.js
- npm
- Jest
- Git
- GitHub
- GitHub Actions

## Жоба құрылымы

```text
nodejs-cicd-lab/
├── src/
│   └── calculator.js
├── test/
│   └── calculator.test.js
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── package.json
├── package-lock.json
└── README.md