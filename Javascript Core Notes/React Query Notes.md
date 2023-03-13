# React Query

- Render same data across multiple components without refetches
- Deduplicate identical requests
- Cache to limit the number of 'fetch' requests
- automatically refetching to have the freshest data
- Handle pagination
- Update local data upon remote data mutation
- Orchestrating dependency requests
- Sensible Defaults
- Fully Configurable


- `npm i react-query
- In main.jsx
  - `import {QueryClient, QueryClientProvider} from 'react-query`
  - `const client=QueryClient();`
  - Wrap <App /> betweeb QueryCLientProvider
    - ```
        <QueryClientProvider client={client}>
            <App/>
        </QueryClientProvider>
      ``` 
-  