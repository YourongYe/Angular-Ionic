# TypeScript variables in HTML
standard: {{variable-name}}

Example 1:
```html
<img class="question-card" src="/assets/Question-card/{{questionCard}}.png"/>
```

Example 2:
```html
<span class="font">{{answerOptions[2]}}</span>
```

# Function call in HTML
In ionic:
```html
<ion-button shape="round" fill="outline" class="choice-button" (click)="updateProgress(4)">
```

In HTML
```html
<button onclick="myFunction()">Click me</button>
```
