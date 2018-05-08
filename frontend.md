# Front-end Challenge

## About the Challenge 

We're using GraphQL here, so thats gonna be the way your going to receive the data(sounds good, right?).

### What you should develop?
Its simple. The user needs to type an address inside a field and be redirected to a products list page. So your job as a front-end engineer will be to create 2 simple screens consuming and sending data to our API.

You can check out a flux sample at: https://www.ze.delivery/ (our production env)

We're   using   GraphQL:    https://www.graphql.com/guides/

### Visual
We want you to feel free to develop the markup the way you want, we have no wireframes or something like that for this task. You will create 2 screens:
  - Home:
    - Needs to have a header, a footer and a input for the user to fill up with the address.
  - Products page:
    - We want to see the products as cards, with the product title, price and buttons to add/remove the product.

### About the API
The   API   link   is:    https://803votn6w7.execute-api.us-west-2.amazonaws.com/dev/public/graphql
  - Home
    - To   find   the   latitude   and   longitude   of   an   address,   please   use   a   google   maps   API.
    - Use   the   following   address   to   find   a   POC:    Rua   Américo   Brasiliense,   São   Paulo . 
    - The   Query   needed   to   get   the   right   POC   (Get   the   first   POC):
        - Query:       http://bit.ly/2uSIRPz
        - Arguments:
          - Algorithm:   "NEAREST".
          - Lat:   Use   as   String.
          - Long:   Use   as   String.
          - Now:   Pass   the   current   Date   formatted.
  - Product   List
      - The   Query   needed   to   get   the   products
        - Query:    http://bit.ly/2vSpmqK
        - Arguments:
          - Id:   id   of   the   POC retrivied from previous query (PocSearch).
          - Search:   if   ""   (empty),   do   not   filters   by   search.
          - CategoryId:   if   0   (Zero)   do   not   filters   by   category.
      - The   Query   needed   to   get   the   category   list
        - Query:    http://bit.ly/2ugVEYE


### Tech Requirements:

- You need to create a repo on GitHub to host your code
- You're not allowed to use any CSS Frameworks (Bootstrap, Bulma, PureCss etc.)
- Avoid using scaffolds (Create React App etc.), we want to see how you make your project structure
- React or Vanilla JS will be a plus, but you can use whatever you want =)
- Tests will be a plus!
- I want to be able to run your project locally by using `npm start`

## Evaluation Method

Your code will be under review of the Zé Delivery Global Engineering team. What we will look for:
- **Good Practices and patterns**
- **Code and Folder Structure**
- **Componentization and data flux**
- **Easy to understand code(no need for fancy stuff)**


Feel free to implement it the way you feel more confortable :)

**Any doubts? You can open issues here and we will get in touch**

