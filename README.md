public class Search{
void searchdetails()
{
    String a[][]={{"name","A","B","C","D","E"},{"date","1992","1988","1980","1989","1990"}};
    String search="E";
    for(int i=0;i<6;i++)
    {
        for(int j=0;j<6;j++)
        {
            if(a[i][j]==search)
            {
            System.out.println(a[i][j]);
            i++;
            System.out.println(a[i][j]);
            break;
            }
        }
    }
}
     public static void main(String []args){
        Search s=new Search();
        s.searchdetails();
     }
}
OUTPUT:
E
1990

