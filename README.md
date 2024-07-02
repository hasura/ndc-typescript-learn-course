# Hasura DDN Native Data Connector in TypeScript Tutorial Companion Repository

This repository is a [companion to the tutorial](https://hasura.io/docs/3.0/connectors/build-your-own/get-started/) 
for building a Hasura DDN connector in TypeScript designed to help you create a data connector in TypeScript for 
Hasura DDN. 

You can follow along with this tutorial to build a connector from scratch or reference the completed version.

## How to Use This Repository

You have two main options:
1. **Follow Along:** Use the `index.ts` file and implement the features step by step as you follow the tutorial.
2. **Reference Finished Code:** Check the `finishedIndex.ts` file to see the completed version of the connector.

All necessary npm packages are already included in the repository.

## Files Overview

- **index.ts:** The main file where you will implement the data connector.
- **finishedIndex.ts:** The completed version of the connector, for reference.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/hasura/ndc-typescript-learn-course.git
   cd ndc-typescript-learn-course
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start Developing:**

    - To build and run the connector and watch for changes:

      ```bash
      npm run dev
      ```

    - Alternatively, you can build and run the connector without watching for changes:

      ```bash
      npm run build && node dist/index.js serve --configuration .
      ```

## Additional Resources

- [Hasura DDN Specification](http://hasura.github.io/ndc-spec/)
- [TypeScript Data Connector SDK](https://github.com/hasura/ndc-sdk-typescript)
- [Hasura DDN Connectors Hub](https://hasura.io/connectors#connectors-list)
- [Hasura DDN Open Source Engine](https://github.com/hasura/graphql-engine/tree/master/v3)

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have improvements!

---

Happy coding! Follow along in the tutorial to build your own data connector and explore the powerful capabilities of 
Hasura DDN. If you have any questions, feel free to open an issue in the repository.