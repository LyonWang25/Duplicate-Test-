## Q1: What changes would you have to make to the application if it came from an API? In what type of hook should you use to fetch the data and why? What other considerations would you have to make?

## Ans:

If it comes from API, I will use useEffect and async await to fetch data.
Also, I will use Redux(dispatch and useSelector ) to store state, so that we won't need to render component as we go to next page or previous page to fetch data again

method 2: Also use useEffect hooks, but we can store data by useMemo to avoid render data as click next page or previous page.

## Q2: Part of this application uses the package nanoid to generate keys. What issue would this cause for generating keys in React?

Although the nanoid documentation states that it should not be used with React, I think it is fine...to use it to create a stable ID in the pagenation component.
