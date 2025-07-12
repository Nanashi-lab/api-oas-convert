# Test component for Swagger UI binding in Golem

## Getting Started

This project demonstrates using Swagger UI bindings in Golem with a single binary approach.

### Prerequisites
- Download the `golem` binary from the [`openapi` branch of golem-cli](https://github.com/Nanashi-lab/golem-cli/tree/openapi).

### Setup & Usage

1. **Start the Golem server:**
   ```sh
   golem server run
   ```

2. **Deploy the applications:**
   - Navigate to each app folder (e.g., `shopping-cart/`, `todo-list/`)
   - Run:
     ```sh
     golem app deploy
     ```

3. **Access Swagger UI:**
   - After deployment, you can access the Swagger UI for each app at the endpoints listed below.

## Shopping Cart

**API:**
- `shopping-cart/0.0.1`
- [localhost:9006/v0.0.1/swagger-shopping-cart](http://localhost:9006/v0.0.1/swagger-shopping-cart)

## Todo List

**APIs:**
- `todo-list1/0.0.1`
  - [localhost:9006/v0.0.1/swagger-todo](http://localhost:9006/v0.0.1/swagger-todo)
- `todo-list2/0.0.2`
  - [localhost:9006/v0.0.2/swagger-todo](http://localhost:9006/v0.0.2/swagger-todo)
- `simple-todo-list/0.0.1`
  - [localhost:9006/v0.0.1/swagger-simple](http://localhost:9006/v0.0.1/swagger-simple)

## LLM

**APIs:**
- `llm/0.0.1`
  - [localhost:9006/v0.0.1/swagger-llm](http://localhost:9006/v0.0.1/swagger-llm)

#Setup for LLM
  1. LLM test component is from golem-llm, LLM expects the wasm files to be under folder components/debug or components/release
  2. You would have to pre-create the worker with the environmental variable, with worker name being **test-llm**

 




