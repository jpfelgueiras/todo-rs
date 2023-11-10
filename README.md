# Part 1 

https://medium.com/@robjsliwa_71070/building-a-multi-tenant-to-do-server-in-rust-part-1-4b90c0604224

# Part 2

https://medium.com/@robjsliwa_71070/building-a-multi-tenant-todo-server-in-rust-part-2-58e2ec137c87

## Generate Token

```
cd genjwt
cargo run -- --secret secret --tenant-id 1 --user-id 1
```
## Run 
```
JWT_SECRET=secret MEMSTORE_PATH=./data.json cargo watch -x run
```

# Part 3

https://medium.com/@robjsliwa_71070/building-a-multi-tenant-to-do-server-in-rust-part-3-6a78c47f800d

# Part 4 

https://medium.com/@robjsliwa_71070/crafting-cli-with-oauth-2-0-authentication-multi-tenant-todo-server-in-rust-series-eaa0af452a56

# Local LLM

https://medium.com/@robjsliwa_71070/easy-as-ollama-running-large-language-models-locally-with-a-elegant-web-ui-af3255b18141