# Bootstrap FAQ Section

Responsive FAQ with Bootstrap 5. Templates include accordion faq, collapse FAQ, FAQ section & customized Bootstrap FAQ components.

FAQ is an abbreviation from "Frequently Asked Questions", FAQ is usually a section of a page or a full page itself. Building a FAQ with the latest Bootstrap 5 usually requires using components like accordion or collapse.

## Basic examples

#### FAQ with Accordion

```html
<div class="accordion w-100" id="basicAccordion">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#basicAccordionCollapseOne" aria-expanded="false"
        aria-controls="collapseOne">
        Question #1
      </button>
    </h2>
    <div id="basicAccordionCollapseOne" class="accordion-collapse collapse"
      aria-labelledby="headingOne" data-mdb-parent="#basicAccordion" style="">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or overriding
        our default variables. It's also worth noting that just about any HTML can go within
        the <code>.accordion-body
```

#### Much more examples and a detailed description can be found at [📄 FAQ Section documentation page](https://mdbootstrap.com/docs/standard/extended/faq/)
