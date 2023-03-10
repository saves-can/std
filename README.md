# STD Clau Standard Modules

These modules try to minimize external dependencies and they are reviewed by the core team. The intention is to have a standard set of high quality code that all Clau projects can use fearlessly.  Contributions are welcome!


## Installation

### Shared 

To use a module in your project, you can import it from a remote URL like this:

```
https://raw.githubusercontent.com/clau-org/std/main/mod.ts
```

### Backend 

To use a module in your Deno project, you can import it from a remote URL like this:

```
https://raw.githubusercontent.com/clau-org/std/main/server/mod.ts
```

### Frontend 

To use a layer in your Nuxt project, you can import it from a remote URL like this:

```
https://raw.githubusercontent.com/clau-org/std/main/client/mod
```

To use a module in your Nuxt project, you can import it from a package like this:

```
@clau-org/client/mod
```

## Usage

Here's an example of how to use the myFunction() function in your project:

```typescript
Copy code
import { myFn } from 'https://raw.githubusercontent.com/clau-org/std/main/mod.ts';

const result = myFn();
console.log(result);
```

The myFn() function returns a string that represents the result of doing X, Y, or Z.


## API documentation

For full documentation of all functions provided by this module, please see the README.md in each module directory in this repository.


## Contributing

Contributions to this module are welcome! To make a contribution, please follow these steps:

Fork the repository.
Make your changes.
Create a pull request.
All contributions must adhere to our code of conduct and be reviewed by a member of the core team before being merged.


## License

This module is distributed under the -- License.


## Maintainers

Francisco Ramos (fro.profesional@gmail.com)

