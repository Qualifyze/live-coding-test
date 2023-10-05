# Qualifyze Live Coding Test

## Context

You are a member of a dev team. Your manager gives you a task, to create a PoC of a client library that would create a reusable code to consume the PetStore API. The API can be found at: https://petstore.swagger.io

By consuming the PetStore API, we mean that the code should communicate with the PetStore API (its endpoints)
and send/retrieve proper data.

For the sake of PoC, focus on a SINGLE endpoint: Create a new Pet (See https://petstore.swagger.io/#/pet/addPet)

Our working student already spent some time on that PoC and provided you this as a starting point:


```typescript
export const createPet = async () => {
 const resp = await fetch(null);
}
```

When implementing the solution, focus on:

* Architecture and flexibility of the solution
* How to model the data
* Good practices when desgining reusable piece of code

It is worth to note that:

* Few teams will use your code
* You have around 35 minutes to create the solution
* It doesn't have to work (you do not have to run it), as we care about the skills to design code solutions
