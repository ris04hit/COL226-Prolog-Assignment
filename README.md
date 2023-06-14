How to execute:

    subsequence:
        As per the specifications
        Sample Query:
            ?- subsequence([c,d,e],[a,b,c,d,e,f]).

    triplicates:
        As per the specifications
        Sample Query:
            ?- has_no_triplicates([1,1,2,2,3,3]).

    arith:
        "prints" the required expression when arith(List) is executed.
        All the expressions in which no extra operator follows "=" sign and no unary "+" sign can be printed by pressing semicolon.
        Sample Query:
            ?- arith([2,3,4,6,9]).

    abcd:
        "prints" the person's name who has paddles twice.
        Then from next line, "prints" all crossings with paddler listed first and rider listed second (if exists).
        Each crossing is printed a new line.
        All the possibilities can be printed by pressing semicolon.
        Sample Query:
            ?- abcd().
        Sample Output:
            Carol
            Davis Alice
            Alice
            Bob Carol
            Carol
            Carol Alice
            true.
        Output Explanation:
            Carol is printed in first line. This means Carol paddled twice. Next five lines contains the description of crossings:
                Crossing Number         Paddler         Rider
                1                       Davis           Alice
                2                       Alice
                3                       Bob             Carol
                4                       Carol
                5                       Carol           Alice
