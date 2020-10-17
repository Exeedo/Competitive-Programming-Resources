# C++
    + Cin / Cout (for input/output)

    + Pair
        - swap                (fuction)
        - first               (fuction)
        - second              (fuction)
        - make_pair           (fuction)
            - example : pair<int, int>, pair<char, int>, pair<string, vector<int>>

    + Vector
        - push_back           (fuction)
        - size                (fuction)
        - empty               (fuction)
        - begin               (fuction)
        - end                 (fuction)
        - rbegin              (fuction)
        - rend                (fuction)
        - clear               (fuction)
        - erase               (fuction)
        ** things to try by yourself **
            for (auto i : vector) tp iterate on vector elements by reference
            for (int i = 0 ; i < vector.size() ; i++) to iterate on vector elements by index
            sort(vector.begin(), vector.end())
            reverse(vector.begin(), vector.end())
        links:
            https://www.geeksforgeeks.org/vector-in-cpp-stl/

    + Map
        note: elements in map are stored as pairs < key, value >
        example: map["Omar"] = 1; here key is (string) , and value is (int)
        ** map is always sorted depending on the key and you never need to sort it **

        - clear               (fuction)

        ** things to try by yourself **
        for (auto p : map) here p is a pair of key and value pair<key, value>
            the key is p.first, value is p.second

        links: 
            https://www.hackerrank.com/challenges/cpp-maps/problem

    + Set
        - emplace             (fuction)
        - erase               (fuction)
        - clear               (fuction)
        - size                (fuction)
        - begin               (fuction)
        - end                 (fuction)
        ** set is always sorted, no need to sort it **
        ** you can never use index to iterate on set, insted you need iteration 
                by reference ** example: for (auto i : set)
        links:
            https://www.hackerrank.com/challenges/cpp-sets/problem
            https://www.geeksforgeeks.org/set-in-cpp-stl/

    + Array
        ** The difference between array and vector is that vector has no constant size, 
               while array has limited constant size and must be deleared with the array **
        example : 
            int arr[100]; 
            char arr[10]

            const int N = 1e5 (it means 1 * 10^5)
            double array[N]
        2D arrays (matrix) : https://www.youtube.com/watch?v=zM0NFyBsPAw 

    + Addtional Resources : 
        - https://www.youtube.com/playlist?list=PLPt2dINI2MIbwnEoeHZnUHeUHjTd8x4F3 
                        (Awesome and Amazing content)

