# Search Engine

- Built a scalable search engine similar to Google or Bing.
- Includes information retrieval concepts like text analysis (tf-idf) and link analysis (PageRank), and parallel data processing with MapReduce.
- Uses a Service-Oriented Architecture to scale dynamic pages and web search.
- Creates a segmented inverted index of web pages using a pipeline of MapReduce programs.
- Built an Index server, a REST API app that returns search results in JSON format.
- Built a Search server, a user interface that returns search results just like Google or Bing.

---

  <p>
    <iframe src="https://c5b0-2600-6c44-74f0-94d0-d488-6c6e-3fdd-db05.ngrok-free.app/" width="100%" height="450" frameborder="0" scrolling="yes"></iframe>  
  </p>  


## Usage Instructions 

- The Search server is a user interface implemented with server-side dynamic pages. A user enters a query and the Search server returns a page of search results.
- The Search server backend makes REST API requests to each Index server and combines the results from each inverted index segment. It makes these requests in parallel threads.
- The Search server then displays the top 10 results to the client.
- To test it type in various queries into and adjust the weights by using the slider to see the variations in results (scroll down to see the search results).

---

Technologies: Python, SQL, Flask, HTML and CSS, JSON
