### Iteration 1 | Component: `Greetings`

Create a `Greetings` component with 2 props:

- `lang`: A string that could be ,`"de"`,`"en"`,`"es"`,`"fr"`
- `children`: A text

![image](https://user-images.githubusercontent.com/5306791/52957158-57edfd80-3391-11e9-8726-93c1a3389016.png)


### Iteration 2 | Component: `CreditCard`

Create a `CreditCard` component that displays a square with a background color based on props. For this. You will need a styled component.

It takes 8 props:

- `type`: A string that can be `"Visa"` or `"Master Card"`
- `number`: A string that is a number of the credit card. You will only display the 4 last digits for security reasons 😉
- `expirationMonth`: A number that represents the month, between 1 and 12
- `expirationYear`: A number that represents the year
- `bank`: A string that represents the name of the bank
- `owner`: A string that represents the name of the owner
- `bgColor`: A string for the background color of the card
- `color`: A string for the text color of the card

Take your time to do as close to the output. You probably have to use flexbox.


**Output**

![image](https://user-images.githubusercontent.com/5306791/52975678-ac5fa000-33c6-11e9-8cbf-7d13a8a0f625.png)


### Iteration 3 | Component: `IdCard`

Create a `IdCard` component with 6 props:

- `lastName`: A string
- `firstName`: A string
- `gender`: A string, `'male'` or `'female'`
- `height`: A number
- `birth`: A date
- `picture`: A string

**Output**

![image](https://user-images.githubusercontent.com/5306791/52976030-22b0d200-33c8-11e9-91fe-e3ce0fa14078.png)


### Iteration 4 | List and Keys | `NumbersTable`

Create a `NumbersTable` component that displays a list of numbers between 1 and a limit. Even numbers must be red.

It takes 1 prop:

- `limit`: A number.

**Example**

```js
<NumbersTable limit={12} />
```

**Output**

![image](https://user-images.githubusercontent.com/5306791/53028410-13349600-3467-11e9-8199-407375e61ab0.png)


### Iteration 5 | Component: `Rating`

Create a `Rating` component that displays 5 stars. Depending on the value received, some stars should be empty (☆), and some should be filled (★).

The component should take 1 prop:

- `children`: A number between `0` and `5`. The value can be a floating-point number. If the number received is `3.9`, the component should display 4 stars.

**Example:**

```jsx
<Rating>0</Rating>
<Rating>1.49</Rating>
<Rating>1.5</Rating>
<Rating>3</Rating>
<Rating>4</Rating>
<Rating>5</Rating>
```

**Expected Output:**

![image](https://user-images.githubusercontent.com/5306791/52972787-39512c00-33bc-11e9-93d8-428d835442fd.png)



----



### Iteration 7 | Component: `DriverCard`

Create a `DriverCard` component that displays a rectangle with content based on the received props. 

The component should take 4 props:

- `name`: A string
- `rating`: A number between `0` and `5`.  The value can be a floating point number.
- `img`: A string
- `car`: An object with properties `model` and `licensePlate`.

**Example**

```jsx
<DriverCard
  name="Travis Kalanick"
  rating={4.2}
  img="https://si.wsj.net/public/resources/images/BN-TY647_37gql_OR_20170621052140.jpg?width=620&height=428"
  car={{
    model: "Toyota Corolla Altis",
    licensePlate: "CO42DE"
  }}
/>

<DriverCard
  name="Dara Khosrowshahi"
  rating={4.9}
  img="https://ubernewsroomapi.10upcdn.com/wp-content/uploads/2017/09/Dara_ELT_Newsroom_1000px.jpg"
  car={{
    model: "Audi A3",
    licensePlate: "BE33ER"
  }}
/>
```

**Expected Output:**

![image](https://user-images.githubusercontent.com/5306791/52972847-66054380-33bc-11e9-92e0-8e48d1ab0212.png)



----

### Iteration 9 | Component: `BoxColor`

Create a `BoxColor` component that displays a rectangle with a background color based on props. For this, you will need a inline style ([documentation](https://reactjs.org/docs/dom-elements.html#style)).

It takes 3 props:

- `r`: A number between 0 and 255 representing the amount of red
- `g`: A number between 0 and 255 representing the amount of green
- `b`: A number between 0 and 255 representing the amount of blue

**Example**

```js
<BoxColor r={255} g={0} b={0} />
<BoxColor r={128} g={255} b={0} />
```

**Output**

![image](https://user-images.githubusercontent.com/5306791/52957816-ec0c9480-3392-11e9-9e00-67094fa2b431.png)

As a bonus, you can also display the hex values of the color (ex: `#ff0000` for red).

### Iteration 8 | Component: `Random`

Create a `Random` component with 2 props:

- `min`: A number
- `max`: A number

**Example**

```js
<Random min={1} max={6}/>
<Random min={1} max={100}/>
```

**Output**

![image](https://user-images.githubusercontent.com/5306791/52957202-718f4500-3391-11e9-9b45-d1172067e877.png)
