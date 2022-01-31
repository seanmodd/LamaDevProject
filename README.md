## Snippets To Remember
**[x]: *rsc* - React Stateless Component**
```
import React from 'react';

const BugsList = () => {
  return (
    <div>
      
    </div>
  );
};

export default BugsList;
```
**[x]: *rsf* - React Stateless Function**
```
import React from 'react';

function BugsList(props) {
  return (
    <div>
      
    </div>
  );
}

export default BugsList;
```
**[x]: *rxaction* - Redux Action**
```
export const first = (payload) => ({
  type: second,
  payload,
});
```
**[x]: *rxconst* - Redux Constant**
```
export const first = 'first';
```
**[x]: *rxreducer* - Redux Reducer**
```
const initialState = {};

export default (state = initialState, { type, payload }) => {
  switch (type) {
    case first:
      return { ...state, ...payload };

    default:
      return state;
  }
};
```
**[x]: *rxselect* - Redux Select**
```
import { createSelector } from 'reselect';

export const first = (state) => state.second;
```
**[x]: *rxslice* - Redux Slice**
```
import { createSlice } from '@reduxjs/toolkit';

const initialState = {};

const BugsList = createSlice({
  name: second,
  initialState,
  reducers: {},
});

export const {} = BugsList.actions;

export default BugsList.reducer;
```


