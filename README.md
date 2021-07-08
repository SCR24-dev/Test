#Optimize ZipCodes
***
This Program is used to remove the overlapping zip code ranges from the give set of zip codes.

To Optimize the set of zip code, I have followed below steps
1.First,Sort the give ranges.
2.Now, we have sorted ranges, so we can find any overlapping value by comparing with previous max value.
3.If there is an overlapping occurs, then optimize the current range with previous range and make it as single range.
4.This single range is now independent with other ranges, it doesnt overlap with previous values.
5.If there is no overlapping, then we will directly consider that range as independent ranges.
6.By iterating 3 to 5 steps over the given set of ranges, At the end of iteration, we will have all the independent ranges which will not overlap with other ranges.