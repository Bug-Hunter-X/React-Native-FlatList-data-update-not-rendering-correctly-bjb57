# React Native FlatList Data Update Issue

This repository demonstrates a common bug in React Native where updating data in a FlatList doesn't result in the UI reflecting the changes. The bug and solution are provided with code samples.

**Bug:** The FlatList component fails to re-render correctly when the underlying data is updated, leading to a stale UI. This can happen due to various reasons, including:

- Incorrect or missing `keyExtractor` function.
- Shallow comparison problems with objects in the data array.
- Incorrect use or omission of the `extraData` prop.

**Solution:** The solution demonstrates how to fix the bug by correctly implementing `keyExtractor`, handling data updates properly, and using `extraData` when necessary.