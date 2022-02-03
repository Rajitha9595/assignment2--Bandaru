# assignment2--Bandaru
# Rajitha Bandaru
###### McDonalds
McDonald's is an **American** fast food company, it's burgers are probably the best example of what fast food should **taste** like. It ranges from spicy to sweet and adds quality taste to the item.

---

# Route to McDonalds from nearest Airport
Tirupati International Airport

1. After stepping out of the airport take Airport Terminal ROad to NH565/NH71 in Tirupati.
2. Turn right to stay on Airport Terminal Road and walk for 5 minutes then Turn right onto Tirupati Airport Road.
3. Turn left at V&E Bike and Car Rental to stay on Tirupati Airport Road and you will find the McDonalds at your left side.

* Chicken Burger
* French Fries
    * Nuggets
    * Fillet-o-fish
* Chicken Sandwich

---

[about_me_link](https://github.com/Rajitha9595/assignment2--Bandaru/blob/main/AboutMe.md)

---
# Physicial Activites
The following table illustrates regarding the sports that I am interested in and would like to suggest to my friends are Badminton,Throw ball, ping pong and tennikoit. <br> The first column should be the name of the sport/activity. <br> The second column will be a location where you can participate in the sport/activity. <br> The third column is the amount of money someone should expect to pay for any personal equipment needed.

| Sports Name | Location | Amount |
|:---         |:---      |:---    |
| Badminton | Badminton court | $10-birdie, $100-Badminton Racquet |
| Throw Ball | Throw Ball court | $50-Teeshirt |
| Ping Pong | Ping Pong Table | $50-Shoes |
| Tennikoit   | Tennikoit court   | $150-Tennikoit RIng |
---

---
# Quotations
> Hurt me with a truth but never comfort me with a lie.- *Rajitha*
>
> Never give up without a fpight.-*Bandaru*
---
# code fencing

>Topological sorting for Directed Acyclic Graph (DAG) is a linear ordering of vertices such that for every directed edge u v, vertex u comes before v in the ordering. Topological Sorting for a graph is not possible if the graph is not a DAG.

<https://www.geeksforgeeks.org/topological-sorting/>
---

topological_sort(N, adj[N][N])
        T = []
        visited = []
        in_degree = []
        for i = 0 to N
                in_degree[i] = visited[i] = 0

        for i = 0 to N
                for j = 0 to N
                        if adj[i][j] is TRUE
                                in_degree[j] = in_degree[j] + 1

        for i = 0 to N
                if in_degree[i] is 0
                        enqueue(Queue, i)
                        visited[i] = TRUE

        while Queue is not Empty
                vertex = get_front(Queue)
                dequeue(Queue)
                T.append(vertex)
                for j = 0 to N
                        if adj[vertex][j] is TRUE and visited[j] is FALSE
                                in_degree[j] = in_degree[j] - 1
                                if in_degree[j] is 0
                                        enqueue(Queue, j)
                                        visited[j] = TRUE
        return T

<https://www.hackerearth.com/practice/algorithms/graphs/topological-sort/tutorial/>
---


