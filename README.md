# Information Retrieval: Assessment 2

## Student Name & Number
Jun Tai - 100325428

## How to run the project
Open the file on Jupyter notebook 'IRassessment2.ipynb'

Run the notebook document step-by-step (one cell a time) by pressing
shift+enter. The python program will receive input, and as such the user
can query any search terms on search engine. In order to exit the
program, type 'quit!'.

## Project Structure

1.  Extracting and clean the important text
2.  Building ranked list of results for each query with search engines
3.  Implementation of the tf-idf calculation with search engine
4.  Building upweighting document zones with search engine
5.  Experiment with query expansion and name entitites

#### Part 1: Extracting and clean the important text (cell 1-2)

Download 'ueapeople.zip' on Blackboard. 
Extract, tokenize and clean the data, return a list of term-frequency pairs for each term

#### Part 2: Building ranked list of results for each query and search engines

Create 2 type of ranked retrieval with its own search engine: single
term ranked (cell 2-4) & multi-term ranked retrieval (cell 5) 
Create 3 tables: 'docIDs', 'vocab', 'postings'. 
Save and load it in the search engine for faster processing time. 
More than or equal to 1 token can be searched in multi-term search engine

#### Part 3: Implementation of the tf-idf calculation with search engine 

create multi-term ranked retrieval search engine with tf*idf calculation
(cell 5) which will return the amount of the documents and its it*idf
score

#### Part 4: Building upweighting document zones with search engine

(Cell 6-9)
Adding upweighting document zone in tokenizor function is effective for the further retrieval function 
Create document zone weighting into the inverted index model 
Save and load the tables in the search engine name of the document and its tf*idf score will be returned in the end

#### Part 5: Experiment with query expansion and name entitites

(Cell 10-13)
Create a simple function to extract, tokenize and clean up the data
Range from expanding acronyms, to add synonyms of query term

Using spacy models for better named entity recognition
