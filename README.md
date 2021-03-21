class heap1{
    public static int arr[]=new int[5];
    public static int capacity=5;
    public static int size=0;
    public static int left(int i){
         return 2*i+1;
    }
    public static int right(int i){
        return 2*i+2;
   }
   public static int parent(int i){
    return (i-1)/2;
}
}
