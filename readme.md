# Angular Commands

1. To install the cli - `npm install -g @angular/cli`

2. To create new project - `ng new PROJECT-NAME`

3. To serve the project - `cd PROJECT-NAME` and `ng serve`

4. To serve to a different port - `ng serve --host 0.0.0.0 --port 4201`
_____________________________

5. Generating Components
    You can use the `ng generate` (or just `ng g`) command to generate Angular components:
    ```bash
    ng generate component my-new-component
    ng g component my-new-component # using the alias

    # components support relative path generation
    # if in the directory src/app/feature/ and you run
    ng g component new-cmp
    # your component will be generated in src/app/feature/new-cmp
    # but if you were to run
    ng g component ../newer-cmp
    # your component will be generated in src/app/newer-cmp
    # if in the directory src/app you can also run
    ng g component feature/new-cmp
    # and your component will be generated in src/app/feature/new-cmp
    ```

6. To install and use bootstrap - `npm install --save bootstrap`. Then add to styles in angular-cli.json file.

7. **Attribute directives** sit on the element just like a normal attribute, **structural directive** basically do the same but they change the structure as well.

[Images](images/screen.png)

