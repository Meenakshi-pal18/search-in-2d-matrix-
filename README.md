# search-in-2d-matrix-
class Solution {
public:
    bool searchMatrix(vector<vector<int>>& matrix, int target) {
        int row=5;
        int col=5;
       // bool res=false;
        for(int i=0;i<row;i++){
            for(int j=0;j<col;j++){
                if(matrix[i][j]==target){
                    return true;
                }
            }
        }
        return false;
    }
};
