## Task Description
These are a set of short tasks to test how developer experience is improved while using an LSP.

Once these tasks are finished you should be able to run see the results by running the following command and visiting localhost:8080 in your browser.
```sh
linx webserver.links
```

## Part 1: Fixing Errors

For each of these tasks, you will need to fix the errors in the provided files.

### mandelbrot.links
mandelbrot.links has been littered with a few typical errors. Your task is to fix these errors.

You may also want to rename the fractal computation function to something a bit more representative of it's output.

### multiple.links
This file file has also been littere d with a few typical errors. Your task is to fix these errors.

## Part 2: Finishing Functions 
For each of these tasks, you will implement a missing function.

### silly-progress.links
For this task, you will implement the `compute` function to recursively count up to a specified total number and update the progress bar on the client-side.

1. Implement the `compute` function so that it recursively calls itself using `computeStep` as the new `count` until `count` reaches `total`.
2. Inside each recursive call, use `showProgress` to update the progress bar.
3. When `count` reaches `total`, return a string indicating that counting is done.

### todo.links
For this task you will need to implement the `remove` function, which takes an item and a list of items as parameters. The function should remove the first occurrence of the specified item from the list and return the updated list.
