 This README provides a comprehensive guide to understanding, building, and using  BigInt library.

# Big Integer Library in C++


[![Contributors](https://img.shields.io/github/contributors/yourusername/BigIntegerLibrary)](https://github.com/yourusername/BigIntegerLibrary/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/yourusername/BigIntegerLibrary)](https://github.com/yourusername/BigIntegerLibrary/issues)
[![Forks](https://img.shields.io/github/forks/yourusername/BigIntegerLibrary)](https://github.com/yourusername/BigIntegerLibrary/network/members)
[![Stars](https://img.shields.io/github/stars/yourusername/BigIntegerLibrary)](https://github.com/yourusername/BigIntegerLibrary/stargazers)

## Overview

The Big Integer Library in C++ provides an efficient implementation of arbitrary-precision arithmetic. This library allows you to perform operations on large integers beyond the typical limits of built-in data types like `int` and `long long`. The library supports basic operations such as addition, subtraction, multiplication, and division, as well as advanced operations like modular arithmetic, exponentiation, and more.

### Features

- **Arbitrary-Precision Arithmetic**: Handle integers of any size without overflow.
- **Efficient Algorithms**: Implemented using optimized algorithms like the Karatsuba algorithm.
- **Memory Management**: Robust handling of large numbers with dynamic memory allocation.
- **Extensible**: Easy to extend with additional mathematical operations.

## Getting Started

### Prerequisites

- A C++ compiler supporting C++11 or higher.
- [CMake](https://cmake.org/) for building the project (optional but recommended).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/BigIntegerLibrary.git
    cd BigIntegerLibrary
    ```

2. Compile the library:
    ```bash
    g++ -std=c++11 -o biginteger main.cpp BigInteger.cpp -I.
    ```

3. Run the tests or examples:
    ```bash
    ./biginteger
    ```

### Usage

Here’s a simple example of how to use the Big Integer Library:

```cpp


##RunningTests

A suite of unit tests is included to verify the functionality of the library. To run the tests:

bash
Copy code
make test

##Contributing


Contributions are welcome! Here's how you can help:

Fork the repository: Click the "Fork" button at the top right of this page.
Create a branch: Create your feature 

branch (git checkout -b feature-branch).

Commit your changes: (git commit -am 'Add some feature').

Push to the branch: (git push origin feature-branch).
Create a Pull Request: Submit your changes for review.

If you find any bugs or have ideas for enhancements, feel free to submit an issue or pull request. All contributions are greatly appreciated!

If you find any bugs or have ideas for enhancements, feel free to submit an issue or pull request. All contributions are greatly appreciated!

##Acknowledgements


This project was inspired by the need for handling very large integers in computational projects. Special thanks to all contributors who helped improve the library.

##Resources

Here are some resources that may help you understand and contribute to the project:

- **[C++ Documentation](http://www.cplusplus.com/)**: Comprehensive reference for C++ programming.
- **[Karatsuba Algorithm](https://en.wikipedia.org/wiki/Karatsuba_algorithm)**: Detailed explanation of the Karatsuba multiplication algorithm on Wikipedia.
- **[Modular Arithmetic](https://www.geeksforgeeks.org/modular-arithmetic/)**: A guide to understanding modular arithmetic on GeeksforGeeks.



##Key Components:

1. **Overview**: Clear and concise description of what the library does, with an emphasis on its features.

2. **Technologies**: List the core technologies used, along with any important algorithms implemented in the library.

3. **Installation**: Detailed installation instructions, including how to clone, build, and use the library.

4. **Usage Example**: A simple code example to demonstrate how to use the library.

5. **Contributing**: Encouragement for contributions, with step-by-step instructions on how to fork, branch, commit, and create a pull request.

6. **Acknowledgements**: A section to thank contributors or inspirations for the project.

7. **Resources**: Useful links for further reading and understanding.


#include "BigInteger.h"

int main() {
    BigInteger num1("12345678901234567890");
    BigInteger num2("98765432109876543210");

    BigInteger sum = num1 + num2;
    std::cout << "Sum: " << sum << std::endl;

    BigInteger product = num1 * num2;
    std::cout << "Product: " << product << std::endl;

    return 0;
}


OUTPUT :


The number of digits in first big integer = 5
first and second are equal!
third is smaller than fourth!
fifth is larger than fourth!
first = 12345
second = 12345
third = 10000
fourth = 100000
fifth = 10000000
After incrementing the value of first is : 12346
Sum of fourth and fifth = 10100000
Product of second and third = 123450000
-------------------------Fibonacci------------------------------
Fibonacci 0 = 0
Fibonacci 1 = 1
Fibonacci 2 = 1
Fibonacci 3 = 2
Fibonacci 4 = 3
Fibonacci 5 = 5
Fibonacci 6 = 8
Fibonacci 7 = 13
Fibonacci 8 = 21
Fibonacci 9 = 34
Fibonacci 10 = 55
Fibonacci 11 = 89
Fibonacci 12 = 144
Fibonacci 13 = 233
Fibonacci 14 = 377
Fibonacci 15 = 610
Fibonacci 16 = 987
Fibonacci 17 = 1597
Fibonacci 18 = 2584
Fibonacci 19 = 4181
Fibonacci 20 = 6765
Fibonacci 21 = 10946
Fibonacci 22 = 17711
Fibonacci 23 = 28657
Fibonacci 24 = 46368
Fibonacci 25 = 75025
Fibonacci 26 = 121393
Fibonacci 27 = 196418
Fibonacci 28 = 317811
Fibonacci 29 = 514229
Fibonacci 30 = 832040
Fibonacci 31 = 1346269
Fibonacci 32 = 2178309
Fibonacci 33 = 3524578
Fibonacci 34 = 5702887
Fibonacci 35 = 9227465
Fibonacci 36 = 14930352
Fibonacci 37 = 24157817
Fibonacci 38 = 39088169
Fibonacci 39 = 63245986
Fibonacci 40 = 102334155
Fibonacci 41 = 165580141
Fibonacci 42 = 267914296
Fibonacci 43 = 433494437
Fibonacci 44 = 701408733
Fibonacci 45 = 1134903170
Fibonacci 46 = 1836311903
Fibonacci 47 = 2971215073
Fibonacci 48 = 4807526976
Fibonacci 49 = 7778742049
Fibonacci 50 = 12586269025
Fibonacci 51 = 20365011074
Fibonacci 52 = 32951280099
Fibonacci 53 = 53316291173
Fibonacci 54 = 86267571272
Fibonacci 55 = 139583862445
Fibonacci 56 = 225851433717
Fibonacci 57 = 365435296162
Fibonacci 58 = 591286729879
Fibonacci 59 = 956722026041
Fibonacci 60 = 1548008755920
Fibonacci 61 = 2504730781961
Fibonacci 62 = 4052739537881
Fibonacci 63 = 6557470319842
Fibonacci 64 = 10610209857723
Fibonacci 65 = 17167680177565
Fibonacci 66 = 27777890035288
Fibonacci 67 = 44945570212853
Fibonacci 68 = 72723460248141
Fibonacci 69 = 117669030460994
Fibonacci 70 = 190392490709135
Fibonacci 71 = 308061521170129
Fibonacci 72 = 498454011879264
Fibonacci 73 = 806515533049393
Fibonacci 74 = 1304969544928657
Fibonacci 75 = 2111485077978050
Fibonacci 76 = 3416454622906707
Fibonacci 77 = 5527939700884757
Fibonacci 78 = 8944394323791464
Fibonacci 79 = 14472334024676221
Fibonacci 80 = 23416728348467685
Fibonacci 81 = 37889062373143906
Fibonacci 82 = 61305790721611591
Fibonacci 83 = 99194853094755497
Fibonacci 84 = 160500643816367088
Fibonacci 85 = 259695496911122585
Fibonacci 86 = 420196140727489673
Fibonacci 87 = 679891637638612258
Fibonacci 88 = 1100087778366101931
Fibonacci 89 = 1779979416004714189
Fibonacci 90 = 2880067194370816120
Fibonacci 91 = 4660046610375530309
Fibonacci 92 = 7540113804746346429
Fibonacci 93 = 12200160415121876738
Fibonacci 94 = 19740274219868223167
Fibonacci 95 = 31940434634990099905
Fibonacci 96 = 51680708854858323072
Fibonacci 97 = 83621143489848422977
Fibonacci 98 = 135301852344706746049
Fibonacci 99 = 218922995834555169026
Fibonacci 100 = 354224848179261915075
-------------------------Catalan------------------------------
Catalan 0 = 1
Catalan 1 = 1
Catalan 2 = 2
Catalan 3 = 5
Catalan 4 = 14
Catalan 5 = 42
Catalan 6 = 132
Catalan 7 = 429
Catalan 8 = 1430
Catalan 9 = 4862
Catalan 10 = 16796
Catalan 11 = 58786
Catalan 12 = 208012
Catalan 13 = 742900
Catalan 14 = 2674440
Catalan 15 = 9694845
Catalan 16 = 35357670
Catalan 17 = 129644790
Catalan 18 = 477638700
Catalan 19 = 1767263190
Catalan 20 = 6564120420
Catalan 21 = 24466267020
Catalan 22 = 91482563640
Catalan 23 = 343059613650
Catalan 24 = 1289904147324
Catalan 25 = 4861946401452
Catalan 26 = 18367353072152
Catalan 27 = 69533550916004
Catalan 28 = 263747951750360
Catalan 29 = 1002242216651368
Catalan 30 = 3814986502092304
Catalan 31 = 14544636039226909
Catalan 32 = 55534064877048198
Catalan 33 = 212336130412243110
Catalan 34 = 812944042149730764
Catalan 35 = 3116285494907301262
Catalan 36 = 11959798385860453492
Catalan 37 = 45950804324621742364
Catalan 38 = 176733862787006701400
Catalan 39 = 680425371729975800390
Catalan 40 = 2622127042276492108820
Catalan 41 = 10113918591637898134020
Catalan 42 = 39044429911904443959240
Catalan 43 = 150853479205085351660700
Catalan 44 = 583300119592996693088040
Catalan 45 = 2257117854077248073253720
Catalan 46 = 8740328711533173390046320
Catalan 47 = 33868773757191046886429490
Catalan 48 = 131327898242169365477991900
Catalan 49 = 509552245179617138054608572
Catalan 50 = 1978261657756160653623774456
Catalan 51 = 7684785670514316385230816156
Catalan 52 = 29869166945772625950142417512
Catalan 53 = 116157871455782434250553845880
Catalan 54 = 451959718027953471447609509424
Catalan 55 = 1759414616608818870992479875972
Catalan 56 = 6852456927844873497549658464312
Catalan 57 = 26700952856774851904245220912664
Catalan 58 = 104088460289122304033498318812080
Catalan 59 = 405944995127576985730643443367112
Catalan 60 = 1583850964596120042686772779038896
Catalan 61 = 6182127958584855650487080847216336
Catalan 62 = 24139737743045626825711458546273312
Catalan 63 = 94295850558771979787935384946380125
Catalan 64 = 368479169875816659479009042713546950
Catalan 65 = 1440418573150919668872489894243865350
Catalan 66 = 5632681584560312734993915705849145100
Catalan 67 = 22033725021956517463358552614056949950
Catalan 68 = 86218923998960285726185640663701108500
Catalan 69 = 337485502510215975556783793455058624700
Catalan 70 = 1321422108420282270489942177190229544600
Catalan 71 = 5175569924646105559418940193995065716350
Catalan 72 = 20276890389709399862928998568254641025700
Catalan 73 = 79463489365077377841208237632349268884500
Catalan 74 = 311496878311103321137536291518809134027240
Catalan 75 = 1221395654430378811828760722007962130791020
Catalan 76 = 4790408930363303911328386208394864461024520
Catalan 77 = 18793142726809884575211361279087545193250040
Catalan 78 = 73745243611532458459690151854647329239335600
Catalan 79 = 289450081175264899454283846029490767264392230
Catalan 80 = 1136359577947336271931632877004667456667613940
Catalan 81 = 4462290049988320482463241297506133183499654740
Catalan 82 = 17526585015616776834735140517915655636396234280
Catalan 83 = 68854441132780194707888052034668647142985206100
Catalan 84 = 270557451039395118028642463289168566420671280440
Catalan 85 = 1063353702922273835973036658043476458723103404520
Catalan 86 = 4180080073556524734514695828170907458428751314320
Catalan 87 = 16435314834665426797069144960762886143367590394940
Catalan 88 = 64633260585762914370496637486146181462681535261000
Catalan 89 = 254224158304000796523953440778841647086547372026600
Catalan 90 = 1000134600800354781929399250536541864362461089950800
Catalan 91 = 3935312233584004685417853572763349509774031680023800
Catalan 92 = 15487357822491889407128326963778343232013931127835600
Catalan 93 = 60960876535340415751462563580829648891969728907438000
Catalan 94 = 239993345518077005168915776623476723006280827488229600
Catalan 95 = 944973797977428207852605870454939596837230758234904050
Catalan 96 = 3721443204405954385563870541379246659709506697378694300
Catalan 97 = 14657929356129575437016877846657032761712954950899755100
Catalan 98 = 57743358069601357782187700608042856334020731624756611000
Catalan 99 = 227508830794229349661819540395688853956041682601541047340
Catalan 100 = 896519947090131496687170070074100632420837521538745909320
-------------------------Factorial------------------------------
Factorial of 0 = 1
Factorial of 1 = 1
Factorial of 2 = 2
Factorial of 3 = 6
Factorial of 4 = 24
Factorial of 5 = 120
Factorial of 6 = 720
Factorial of 7 = 5040
Factorial of 8 = 40320
Factorial of 9 = 362880
Factorial of 10 = 3628800
Factorial of 11 = 39916800
Factorial of 12 = 479001600
Factorial of 13 = 6227020800
Factorial of 14 = 87178291200
Factorial of 15 = 1307674368000
Factorial of 16 = 20922789888000
Factorial of 17 = 355687428096000
Factorial of 18 = 6402373705728000
Factorial of 19 = 121645100408832000
Factorial of 20 = 2432902008176640000
Factorial of 21 = 51090942171709440000
Factorial of 22 = 1124000727777607680000
Factorial of 23 = 25852016738884976640000
Factorial of 24 = 620448401733239439360000
Factorial of 25 = 15511210043330985984000000
Factorial of 26 = 403291461126605635584000000
Factorial of 27 = 10888869450418352160768000000
Factorial of 28 = 304888344611713860501504000000
Factorial of 29 = 8841761993739701954543616000000
Factorial of 30 = 265252859812191058636308480000000
Factorial of 31 = 8222838654177922817725562880000000
Factorial of 32 = 263130836933693530167218012160000000
Factorial of 33 = 8683317618811886495518194401280000000
Factorial of 34 = 295232799039604140847618609643520000000
Factorial of 35 = 10333147966386144929666651337523200000000
Factorial of 36 = 371993326789901217467999448150835200000000
Factorial of 37 = 13763753091226345046315979581580902400000000
Factorial of 38 = 523022617466601111760007224100074291200000000
Factorial of 39 = 20397882081197443358640281739902897356800000000
Factorial of 40 = 815915283247897734345611269596115894272000000000
Factorial of 41 = 33452526613163807108170062053440751665152000000000
Factorial of 42 = 1405006117752879898543142606244511569936384000000000
Factorial of 43 = 60415263063373835637355132068513997507264512000000000
Factorial of 44 = 2658271574788448768043625811014615890319638528000000000
Factorial of 45 = 119622220865480194561963161495657715064383733760000000000
Factorial of 46 = 5502622159812088949850305428800254892961651752960000000000
Factorial of 47 = 258623241511168180642964355153611979969197632389120000000000
Factorial of 48 = 12413915592536072670862289047373375038521486354677760000000000
Factorial of 49 = 608281864034267560872252163321295376887552831379210240000000000
Factorial of 50 = 30414093201713378043612608166064768844377641568960512000000000000
Factorial of 51 = 1551118753287382280224243016469303211063259720016986112000000000000
Factorial of 52 = 80658175170943878571660636856403766975289505440883277824000000000000
Factorial of 53 = 4274883284060025564298013753389399649690343788366813724672000000000000
Factorial of 54 = 230843697339241380472092742683027581083278564571807941132288000000000000
Factorial of 55 = 12696403353658275925965100847566516959580321051449436762275840000000000000
Factorial of 56 = 710998587804863451854045647463724949736497978881168458687447040000000000000
Factorial of 57 = 40526919504877216755680601905432322134980384796226602145184481280000000000000
Factorial of 58 = 2350561331282878571829474910515074683828862318181142924420699914240000000000000
Factorial of 59 = 138683118545689835737939019720389406345902876772687432540821294940160000000000000
Factorial of 60 = 8320987112741390144276341183223364380754172606361245952449277696409600000000000000
Factorial of 61 = 507580213877224798800856812176625227226004528988036003099405939480985600000000000000
Factorial of 62 = 31469973260387937525653122354950764088012280797258232192163168247821107200000000000000
Factorial of 63 = 1982608315404440064116146708361898137544773690227268628106279599612729753600000000000000
Factorial of 64 = 126886932185884164103433389335161480802865516174545192198801894375214704230400000000000000
Factorial of 65 = 8247650592082470666723170306785496252186258551345437492922123134388955774976000000000000000
Factorial of 66 = 544344939077443064003729240247842752644293064388798874532860126869671081148416000000000000000
Factorial of 67 = 36471110918188685288249859096605464427167635314049524593701628500267962436943872000000000000000
Factorial of 68 = 2480035542436830599600990418569171581047399201355367672371710738018221445712183296000000000000000
Factorial of 69 = 171122452428141311372468338881272839092270544893520369393648040923257279754140647424000000000000000
Factorial of 70 = 11978571669969891796072783721689098736458938142546425857555362864628009582789845319680000000000000000
Factorial of 71 = 850478588567862317521167644239926010288584608120796235886430763388588680378079017697280000000000000000
Factorial of 72 = 61234458376886086861524070385274672740778091784697328983823014963978384987221689274204160000000000000000
Factorial of 73 = 4470115461512684340891257138125051110076800700282905015819080092370422104067183317016903680000000000000000
Factorial of 74 = 330788544151938641225953028221253782145683251820934971170611926835411235700971565459250872320000000000000000
Factorial of 75 = 24809140811395398091946477116594033660926243886570122837795894512655842677572867409443815424000000000000000000
Factorial of 76 = 1885494701666050254987932260861146558230394535379329335672487982961844043495537923117729972224000000000000000000
Factorial of 77 = 145183092028285869634070784086308284983740379224208358846781574688061991349156420080065207861248000000000000000000
Factorial of 78 = 11324281178206297831457521158732046228731749579488251990048962825668835325234200766245086213177344000000000000000000
Factorial of 79 = 894618213078297528685144171539831652069808216779571907213868063227837990693501860533361810841010176000000000000000000
Factorial of 80 = 71569457046263802294811533723186532165584657342365752577109445058227039255480148842668944867280814080000000000000000000
Factorial of 81 = 5797126020747367985879734231578109105412357244731625958745865049716390179693892056256184534249745940480000000000000000000
Factorial of 82 = 475364333701284174842138206989404946643813294067993328617160934076743994734899148613007131808479167119360000000000000000000
Factorial of 83 = 39455239697206586511897471180120610571436503407643446275224357528369751562996629334879591940103770870906880000000000000000000
Factorial of 84 = 3314240134565353266999387579130131288000666286242049487118846032383059131291716864129885722968716753156177920000000000000000000
Factorial of 85 = 281710411438055027694947944226061159480056634330574206405101912752560026159795933451040286452340924018275123200000000000000000000
Factorial of 86 = 24227095383672732381765523203441259715284870552429381750838764496720162249742450276789464634901319465571660595200000000000000000000
Factorial of 87 = 2107757298379527717213600518699389595229783738061356212322972511214654115727593174080683423236414793504734471782400000000000000000000
Factorial of 88 = 185482642257398439114796845645546284380220968949399346684421580986889562184028199319100141244804501828416633516851200000000000000000000
Factorial of 89 = 16507955160908461081216919262453619309839666236496541854913520707833171034378509739399912570787600662729080382999756800000000000000000000
Factorial of 90 = 1485715964481761497309522733620825737885569961284688766942216863704985393094065876545992131370884059645617234469978112000000000000000000000
Factorial of 91 = 135200152767840296255166568759495142147586866476906677791741734597153670771559994765685283954750449427751168336768008192000000000000000000000
Factorial of 92 = 12438414054641307255475324325873553077577991715875414356840239582938137710983519518443046123837041347353107486982656753664000000000000000000000
Factorial of 93 = 1156772507081641574759205162306240436214753229576413535186142281213246807121467315215203289516844845303838996289387078090752000000000000000000000
Factorial of 94 = 108736615665674308027365285256786601004186803580182872307497374434045199869417927630229109214583415458560865651202385340530688000000000000000000000
Factorial of 95 = 10329978488239059262599702099394727095397746340117372869212250571234293987594703124871765375385424468563282236864226607350415360000000000000000000000
Factorial of 96 = 991677934870949689209571401541893801158183648651267795444376054838492222809091499987689476037000748982075094738965754305639874560000000000000000000000
Factorial of 97 = 96192759682482119853328425949563698712343813919172976158104477319333745612481875498805879175589072651261284189679678167647067832320000000000000000000000
Factorial of 98 = 9426890448883247745626185743057242473809693764078951663494238777294707070023223798882976159207729119823605850588608460429412647567360000000000000000000000
Factorial of 99 = 933262154439441526816992388562667004907159682643816214685929638952175999932299156089414639761565182862536979208272237582511852109168640000000000000000000000
Factorial of 100 = 93326215443944152681699238856266700490715968264381621468592963895217599993229915608941463976156518286253697920827223758251185210916864000000000000000000000000

Project Structure

BigIntCPP/
├── CMakeLists.txt
├── README.md
├── include/
│   └── BigInt.h
├── src/
│   └── BigInt.cpp
├── tests/
│   └── test_bigint.cpp
└── examples/
    └── example_usage.cpp




