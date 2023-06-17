public class Anagram
{

String ascsortMerge(String s)
{
char c[]=new char[s.length()];

    for(int i=0;i<c.length;i++)
    {
    c[i]=s.charAt(i);
    }
    
    for(int i=0;i<c.length;i=i+1)
    {
        for(int j=i+1;j<c.length;j=j+1)
        {
            if(c[i]>c[j])
               {
               char temp=c[i];
               c[i]=c[j];
               c[j]=temp;
               }
        }
    }

    String s3="";
    
    for(int i=0;i<c.length;i++)
    {
    s3=s3+c[i];
    }
System.out.println(s3);
return s3;
  
}


public static void main(String args[])
{

String s1="desserts";
String s2="stressed";

Anagram anagram=new Anagram();

String a=anagram.ascsortMerge(s1);
String b=anagram.ascsortMerge(s2);

  if(a.equals(b))
    {
    System.out.println("Anagram");
    }
    else
    {
    System.out.println("Not Anagram");
    }
}
}

/*
Output::
deerssst
deerssst
Anagram
*/
/*
String s1="dessers"; //If I change spelling the output will be
String s2="stressed";
Output::
deersss
deerssst
Not Anagram
*/
