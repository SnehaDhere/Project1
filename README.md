# Customer

public class Cust
{
    int custAccNo;
    String custName;
    int custValue;

    void setCustAccNo(int custAccNo)
    {
        this.custAccNo=custAccNo;
    }
    int getCustAccNo()
    {
        return custAccNo;
    }
    void setCustName(String custName)
    {
        this.custName=custName;
    }
    String getCustName()
    {
        return custName;
    }
    void  setCustValue(int custValue)
    {
        this.custValue=custValue;
    }
    int getCustValue()
    {
        return custValue;
    }
}


# Main
public class Main1 {
    public static void main(String[] args) {
        Cust c1=new Cust();
        c1.setCustAccNo(100);
        c1.setCustName("Sneha");
        c1.setCustValue(20000);

        System.out.println("Cust acc no is="+c1.getCustAccNo());
        System.out.println("Cust nme is="+c1.getCustName());
        System.out.println("Cust value is="+c1.getCustValue());
    }
}
