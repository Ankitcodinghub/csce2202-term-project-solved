# csce2202-term-project-solved
**TO GET THIS SOLUTION VISIT:** [CSCE2202 Term Project Solved](https://www.ankitcodinghub.com/product/csce2202-guidelines-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118634&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCE2202 Term Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Project Components

• A problem to be defined

• Adopted methodology for the solution

• Implementation of one or more algorithms in the adopted methodology

• Choice of your input experimental data

• Demonstrations by your processing of input experimental data

• Analysis of algorithms used and your output experimental results as well as critique of methodology used

• Conclusions

Suggested Project Report Format

Project Title

Group Name/s

Abstract:

……………………………………………………………………………………………………………

……………………………………………………

Keywords:

___________________________________________________________________________

1. Introduction

(Introduce the topic of the project here)

……………………………………………………………………………………………………………

2. Problem Definition

(Present here a more detailed definition of the topic or problem)

……………………………………………………………………………………………………………

3. Methodology

(Outline the methodology chosen to solve the problem)

……………………………………………………………………………………………………………

4. Specification of Algorithms to be used 5. Data Specifications

……………………………………………………………………………………………………………

(Specify the input data to be used in your work)

……………………………………………………………………………………………………………

6. Experimental Results

(Give your results of processing the input data in text, tabular or graphical forms)

……………………………………………………………………………………………………………

7. Analysis and Critique

(Your own analysis and critique of the output results and the methodology/algorithms used)

……………………………………………………………………………………………………………

8. Conclusions Acknowledgements

……………………………………………………………………………………………………………

(Acknowledge other people who helped you in producing the project)

…………………………….

References

(List here the references you used to produce the project)

…………..………………………………………….

Appendix: Listing of all Implementation Codes

…………..

…………..

Project (1)

Text Compression Utility

ASCII files can be compressed to smaller sizes by using variable length Huffman Coding. By analyzing the different probabilities of the various symbols that occur in a given file, we can build a Huffman tree to come up with a minimal, optimized binary list of code words for these symbols.

Algorithm

The Project:

In this project, you will be implementing a compression utility for ASCII-encoded text. Your program should be able to both compress and decompress text files, and to compute the compression ratio and the efficiency of your encoding. The steps to implement this program are as follows:

1. Determine the symbols / characters used in the file, build your alphabet and probabilities of the symbols.

2. Build a merge tree to find the optimal prefix binary coding for each symbol.

3. Encode your characters with the new binary codes.

4. Save the coded characters along with your code table in the output compressed file.

For decompression, your program should read the code table / tree from the compressed file and use that to recover the original non-compressed text file.

Optimally, your program should have three different parameters passed to it at runtime:

1. A flag indicating whether it is being used to compress or decompress the input file.

2. The path of the input text file.

3. The path to write the output file (compressed file in case of compression, text file in case of decompression).

When used for compression, your program should output the compression ratio (for ASCIIencoded files where each character is written in 8 bits, the compression ratio will be &lt; L&gt; / 8) and the efficiency (η) of your encoding.

Submission Instructions

Grading

The program will be tested against a sample test file to compress it, check the size of the compressed file, and then used again to decompress the file to obtain the original text file. If your program works, it should be capable of producing a smaller sized compressed file, and it should be able to decompress the file to obtain the original file. In this case, grading will be on both the program and the project report.

___________________________________________________________________________

Project (2)

Given a test file, treat each sentence in the file as a potential pattern. Search for the pattern in the existing documents and find the matches.

This problem is typically approached through string matching. In the string matching problem, we are given a string of n characters called the text and a string of m characters (m ≤ n) called the pattern and we want to find a substring of the text that matches the pattern. More precisely, we want to find in the text the start index of the first substring that matches the pattern, if it exists.

Algorithms

There are several algorithms designed to find the location where one or several strings (patterns) are found within a larger string or text. A summary of the most famous methods for string matching is given in the following:

1. Brute Force Matching using Hamming Distance:

The definition of closest follows the Hamming-distance concept. In this method, the Hamming Distance between two strings follows the algorithm below:

For two strings X, Y, where length(X)| ≤ length (Y) A match occurs at position k if A(k) = B(k).

M = Number of matches

Distance = Number of mismatches D = length(Y)) – M

D = 0 if X and Y are identical

2. The Rabin-Karp Algorithm

This is a string-searching algorithm created by Richard M. Karp and Michael O. Rabin (1987) that uses hashing to find an exact match of a pattern string in a text.

3. The KMP Algorithm

This is a string-searching algorithm created by Donald Knuth, James H. Morris, and Vaughan Pratt (1977). The algorithm searches for occurrences of a pattern string within a main “text string” by employing the observation that when a mismatch occurs, the pattern itself embodies sufficient information to determine where the next match could begin, thus bypassing re-examination of previously matched characters.

4. The Boyer–Moore Algorithm

This is an efficient string-searching algorithm that is the standard benchmark for practical string-search. It was developed by Robert S. Boyer and J Strother Moore in 1977. The algorithm preprocesses the string being searched for (the pattern), but not the string being searched in (the text). It is thus well-suited for applications in which the pattern is much shorter than the text or where it persists across multiple searches. The Boyer–Moore algorithm uses information gathered during the preprocess step to skip sections of the text, resulting in a lower constant factor than many other string search algorithms. In general, the algorithm runs faster as the pattern length increases. The key features of the algorithm are to match on the tail of the pattern rather than the head, and to skip along the text in jumps of multiple characters rather than searching every single character in the text.

The Project:

• Build a collection (corpus) of existing documents and a potentially plagiarized document (the choice and number of corpus documents, the size of the document and the potentially plagiarized document are left to your discretion).

• Implement the following basic detectors:

1. Approximate string matching using Brute Force and Hamming Distance

2. Rabin–Karp algorithm

3. Knuth–Morris–Pratt algorithm (KMP Algorithm)

4. Boyer–Moore string-search algorithm

• Using the corpus, find the documents from which the potential document was plagiarized. Given a test file, treat each sentence in the file as a potential pattern. Using the above algorithms, search for the pattern in the existing documents and find the matches.

• Compare the performance of the implemented algorithms (measures of performance are left to your discretion).

Submission Instructions

Grading

___________________________________________________________________________

Project (3)

Finding the Minimum Spanning Tree (MST) for a Graph

In many problems, we choose to represent the relationships between problem entities as a connected, edge-weighted undirected graph with |V| vertices and |E| edges. For such graph G(V,E), a sub-graph S(V,T) is a spanning tree of the graph (G) if:

1. V(S) = V(G) and T ⊆ E

2. S is a tree, i.e., S is connected, has no cycles and |T| = |V|-1

In this case, a spanning tree is a subset of the edges of a connected, edge-weighted undirected graph that connects all the vertices together, without any cycles.

For a connected edge-weighted undirected graph, there could be more than one spanning tree.

The cost of a spanning tree is the sum of the weights of its edges. A Minimum Spanning Tree (MST) is a spanning tree of the graph with minimum cost.

There are several problems that can be solved by finding minimum spanning trees. These include design of computer networks, telecommunications networks, transportation networks, water supply networks, and electrical grids. An example is cable laying for telecommunication among communication points and road paving between houses.

Algorithms

The Project

Your project is to build a Minimum Spanning Tree Utility for a connected, edge-weighted undirected graph.

As an application, a telecommunications authority wishes to lay cables in a new housing compound. It is constrained to bury the cables only along certain roads. This can be represented as a graph containing the houses connected by the cables (edges). Some of the edges might be more expensive, because they are longer, or require the cable to be buried deeper; these paths would be represented by edges with larger weights. Cable laying cost is an acceptable unit for edge weight.

The cable network can be represented by a graph with V nodes (houses) and the weights on the edges represent the cable laying cost between pairs of houses. In this case, our problem would be to find a Minimum Cost Spanning Tree (MST) for the given network. Such a MST would be connected (i.e., there is a cable from every house to every other house) and the sum of weights of edges in that tree would be minimum (i.e., the cost of cable laying be minimum).

You are required to:

• Generate text files that contain the adjacency matrix representations for connected edgeweighted non-directed graphs for layouts with different number V of houses (say V = 8, 16 , 32 , 64). Each graph is connected and the weights are all positive integers in the range 20 – 100. Zero weight represents the absence of a road, or the distance between a house and itself. The houses can be numbered (0,1,2,…) or (A,B,C,….). The first number in the file is the number of houses (V). The following V numbers represent the first row in the adjacency matrix, followed by V numbers representing the second row, and so on.

• Implement both Kruskal’s and Prim’s algorithms for finding the MST for a graph.

• Using the above algorithms, find the MST’s for the graphs generated.

• Compare the performance of the implemented algorithms (measures of performance are left to your discretion).

Notes on the design and implementation:

• The vertices can be given numbers (0,1,….V-1) where V is the actual no. of vertices in the graph given in the file. These numbers can be mapped to names (e.g A,B,C…).

• The zip file “Test_Kruskal.rar” contains a test graph file “testgraph.txt” representing a graph of 7 vertices. You can test your implementation using this file. The sample output for that file is also given in file “sample output.txt”.

1. Set number of vertices V

2. Set minimum and maximum edge weights Wmin , Wmax

3. Seed random number generator

5. Replace values less than Wmin by zeros

6. Put zeros on the diagonal A(i,i), i = 0..V-1

7. For each row above the diagonal, copy it to the corresponding column below the diagonal

This is the final adjacency matrix

8. Reshape the 2-D array A into a 1-D array B of size V2 (row by row)

9. In a text file, write the dimension V followed by the array B

Submission Instructions

Grading

The program will be tested against a sample graph. If your program works, it should be capable of producing the graph MST. In this case, grading will be on both the program and the project report.
