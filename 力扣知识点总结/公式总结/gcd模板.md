```c
// a 和 b均可等于0
int gcd(int a, int b)

{

    return b > 0 ? gcd(b, a % b) : a;

}

int gcd(int a, int b)

{

    if(b == 0)

    {

        return a;

    }

    return gcd(b, a % b);

}
```