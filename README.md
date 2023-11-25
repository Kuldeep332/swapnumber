# swapnumber
{
    public  static void swap(ArrayList<Integer> list,int one,int two){
int temp=list.get(one);
        list.set(one,list.get(two));
        list.set(two,temp);
    }
    public static void main(String[] args) {
        ArrayList<Integer>list=new ArrayList<>();
        list.add(1);
        list.add(3);
        list.add(5);
        list.add(4);
        int index=1; int index1=3;
        System.out.println(list);
        swap(list,index,index1);
        System.out.println(list);

    }
}
