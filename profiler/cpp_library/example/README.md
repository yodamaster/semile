Use the following to give profile specificaiton
* **SEMILE**: define a profile scope
* **SEMILE_n(**_abc_**)**: define a profile scope with name _abc_  
* **SEMILE_MSG**: add debug message in current scope  


Check <a href='https://github.com/r-kan/semile/blob/master/profiler/cpp_library/example/quicksort.cpp'>quicksort.cpp</a> for a complete example with code snippet:
```cpp
void quicksort(vector<int>& x, int start_pos, int end_pos)
{
  SEMILE;
  SEMILE_MSG(GetStr(x, start_pos, end_pos));
  ...
  int pivot = start_pos;
  SEMILE_MSG("pivot: " + GetStr(x[pivot]) + "\\n");
  ...
  Swap(x, i, j);  
  SEMILE_MSG(GetStr(x[i]) + " <=> " + GetStr(x[j]) + "\\n");
}
```
