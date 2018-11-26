# Elite Therapy Providers Website

> Angular 7.0.x app served through Angular CLI, styled using [Sass](https://sass-lang.com/) using [ngx-bootstrap](https://valor-software.com/ngx-bootstrap/#/)

## Improvements

- [ ] add more content @kevin
- [ ] typeform content from @kevin
- [ ] add testing framework

## Development server

1. To run the elite-therapy app you’ll first need to install Angular CLI.

```
npm install -g @angular/cli
```

2. Clone the repository and install dependencies.

```
git clone https://github.com/elite-therapy-providers/elitetherapyproviders.com.git
cd elitetherapyproviders.com
npm install
```

3. Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

```
ng serve
```

## Build

1. Build gh-pages project and store in the `docs` directory.

```
ng build --prod --output-path docs --base-href /
```

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
