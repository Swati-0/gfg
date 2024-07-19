class Solution{
    public:
    long long findMinDiff(vector<long long> a, long long n, long long m){
    //code
    sort(a.begin(), a.end());
    int i=0;
    int r=m-1;
    int mini=INT_MAX;
    int ans=0;
    while(r<n){
        ans=a[r]-a[i];
        mini=min(mini,ans);
        i++;
        r++;
    }
    return mini;
    }   
};
