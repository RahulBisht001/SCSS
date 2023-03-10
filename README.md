# Scss
## CSS with superpowers
#### Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.

## 😕 >> Why to use Scss ?


##  🤔 ❓ What is Difference between Sass and Scss ?
   `Sass (Syntactically Awesome Style Sheets)`  and  `SCSS (Sassy CSS)` are both preprocessors
for CSS.  They both extend the basic functionality of CSS by adding variables, mixins, nesting, and other features to make CSS more powerful and easier to write.

The primary difference between Sass and SCSS is the syntax. Sass uses the `.sass` file extension and uses a whitespace-based syntax. SCSS uses the `.scss` file extension and has a syntax similar to CSS with braces and semicolons.

### Differences
1. Syntax: As mentioned above, Sass has a whitespace-based syntax while SCSS has a syntax similar to CSS.
2. File extension: Sass files have a .sass extension while SCSS files have a .scss extension.
3. Compatibility: SCSS is more widely used and supported by various tools and libraries.
4. Learning curve: Sass has a steeper learning curve due to its unique syntax, while SCSS is easier to learn for those who are familiar with CSS.
5. Migration: Migrating from Sass to SCSS is relatively easy, but the reverse migration can be more challenging.
___________________________________________


# 💪🏻 Powers of Scss




###  1.> Operators 
 Scss provides a number of operators that can be used for mathematical calculations, 
string manipulation, and logical operations. Here are some of the most commonly used
operators in SCSS:

* Mathematical Operators:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Modulus (%)
These operators can be used to perform basic arithmetic operations, such as adding, subtracting, multiplying, dividing, and finding the remainder of a division operation.

* Comparison Operators:
Equal to (==)
Not equal to (!=)
Greater than (>)
Less than (<)
Greater than or equal to (>=)
Less than or equal to (<=)
These operators are used to compare values and return a Boolean (true or false) value based on the comparison result.

* Logical Operators:
And (&&)
Or (||)
Not (!)
These operators are used to combine multiple conditions and return a Boolean value based on the logical result.

* String Operators:

Concatenation (#{$variable} + "text")
The concatenation operator is used to combine multiple strings into a single string value. This is useful for creating dynamic CSS classes and for constructing complex selectors.

These operators can be used to perform a wide range of operations in SCSS, from simple arithmetic calculations to complex conditional statements. By using these operators effectively, you can create more efficient, maintainable, and scalable stylesheets.



```
rem = px / base

where "base" is the font-size of the root element (typically the <html> element) in your CSS.

eg. if your base font-size is set to 16px, and you want to convert 24px to rems,
the calculation would be:

rem = 24px / 16px = 1.5rem

So, 24px is equivalent to 1.5rem in this case.
```


###  2.> Variables

Variables in SCSS allow you to define a value once and reuse it throughout 
your stylesheet. Here's how to create a variable in SCSS:

``` scss
$variable-name: value;
```


``` scss
$base-font-size: 16px;
```

Once you've defined a variable, you can use it in your CSS using the #{$variable-name}

```
body {
  font-size: $base-font-size;
}
```

Now we can use variables in css3 although.


###  3.> Nesting

  Nesting in SCSS allows you to nest selectors inside one another to 
create more organized and readable stylesheets. Here's an example of how to
nest selectors in SCSS:

``` css
nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;

    li {
      display: inline-block;

      a {
        text-decoration: none;

        &:hover {
          text-decoration: underline;
        }
      }
    }
  }
}

```
