# useFetch Hook

Example of use:

```
  const url = <API_URL>;
  const { data, loading, null } = useFetch(url);

  We could see 2 situations:

  1.- Data not fetched

  - data is null
  - loading is true
  - error is null or not

  2.- Data is fetched

  - data is completed with the corresponding values
  - loading is false
  - error is null or not

```
