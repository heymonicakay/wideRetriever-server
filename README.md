# Wide Retriever Server

## Accessing The Sample Data

You will need [JSON Server](https://www.npmjs.com/package/json-server) installed in order to create the persistant data storage.

1. From the GitHub repository, click <kbd>&#x2913; Code</kbd>
2. Copy <kbd>⌘C</kbd> the SSH URL.
3. Open your Terminal.
    > Applications > Utilities > Terminal

4. Change the current working directory to the location where you want the cloned directory.
5. Type `git clone`, and then paste <kbd>⌘V</kbd> the SSH URL you copied.
    ```sh
    git clone git@github.com:heymonicakay/wideRetriever-server.git
    ```
6. Press <kbd>Enter</kbd> to create your local clone.
7. Navigate into the newly created `wideRetriever-server` directory.
    ```sh
    cd wideRetriever-server
    ```
8. To start the JSON Server, run the following command in your Terminal inside of the Wide Retriever Server directory:
    ```sh
    json-server -p 8088 -w db.json
    ```