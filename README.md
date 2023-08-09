# Flight Booking - Web Application using Angular, TypeScript + ASP.NET


# Day1 - Angular & ASP.NET Core
## Multi-page VS Single-page
![MPA.png](pic/MPA(Multo-page%20Application).png)
## SPA(Single-page Angular)

## Angular
1. Angular -> TypeScript
2. Javascript Runs on Browsers
3. TS Typescript
```typescript
app.componen.ts file:
class AppComponent {

}

//Export the class from the outside of the file
export class AppComponent {
    //name: title; field: string
    title: string = 'app'; 
    title = 'app';
    items: stringp[] = ['item 1', 'item 2'];
}


//TypeScript Array Field
export class AppComponent {
    log(text: string): void { 
        var message: string = 'Message' + text;
        console.log(message);
    }
    //public by default
    private log(text: string) : void {...}
    items = ['item 1', 'item 2'];

    f() {
        this.log(...);
        this.items...
    }
}
```

```typescript
var a: number[]
var a: string[]
var a: boolean[]
var app: AppComponent[]
```
2. TypeScript in aciton
```typescript
@Component({...})
export class AppComponent{

}

@Component({
    selector: 'app-root',
    templateUrl: './app.component.html'
})
export class AppComponent {

}
```
3. Angular - self-definced type
```html
<body>
    <app-root>
    </app-root>
</body>
```