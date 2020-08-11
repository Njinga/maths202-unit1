<template>
    <mdb-container>
        <!-- -->
        <section class="text-center white-text special-color  py-3 px-3">
            <h4 class="pt-2 pb-2 text-center"> UNIT 1: Multi-variable functions</h4>
        </section>
        <section class="text-center dark-grey-text mb-4 mt-4">
            <h4 class="font-weight-bold pb-4 text-center">
                <mdb-icon icon="marker" size="lg" class="mr-3" />
                Learning outcomes
                <mdb-icon icon="graduation-cap" size="lg" class="ml-3" />
            </h4>
            <mdb-row class="text-left">
                <!-- Choose appropriate mdb-col  -->
                <mdb-col class="text-left w-responsive mx-auto m-3">
                    <p>
                        <ul>
                            <li>
                                <strong><em>Identify</em></strong> and <strong><em>sketch</em></strong> the domain and range of
                                functions of two variables.
                            </li>
                            <li><strong><em>Derive</em></strong> revenue and profit functions from given cost data and demand schedule.</li>
                            <li>
                                <strong><em>Define</em></strong> and <strong><em>compute</em></strong> the first and second order partial derivatives of functions
                                of two or more variables.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>calculate</em></strong>
                                marginal quantities, such as cost, profit,
                                revenue, productivity and utility, and interpret the results.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>determine</em></strong>
                                whether products are complementary or substitutes.
                            </li>
                            <li>
                                <strong><em>Construct</em></strong> and <strong><em>solve</em></strong> unconstrained optimization problems, defined as functions of two
                                variables, using the second partial derivative test.
                            </li>
                            <li>
                                <strong><em>Formulate</em></strong> and <strong><em>solve</em></strong> constrained optimization problems using the substitution method
                                and the method of Lagrange Multipliers.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>solve</em></strong> a class of optimization problems with applications in
                                business and economics. Examples to include
                            
                            <ul>
                                <li>	Minimising costs subject to production quotas.</li>
                                <li>	Maximising utility subject to budgetary constraints</li>
                                <li> Maximising production subject to a cost constraint. </li>
                            </ul>
                                </li>
                        </ul>
                    </p>
                </mdb-col>

                <mdb-col class="text-left w-responsive mx-auto m-3">

                </mdb-col>   
            </mdb-row>
        </section>
        <hr />
        <!--PARTIAL DERIVATIVES START HERE-->
        <section class="text-center dark-grey-text mb-4 mt-4">
            <h4 class="font-weight-bold pb-4 text-center">Introduction</h4>
            <mdb-row>
                <!-- Choose appropriate mdb-col  -->
                <mdb-col>
                </mdb-col>
            </mdb-row>
        </section>
        <hr />
        <section class="text-justify dark-grey-text mb-4">
            <h4 class="font-weight-bold pb-4 text-center"> Partial Derivatives</h4>
            <mdb-row>
                <!-- Choose appropriate mdb-col  -->
                <mdb-col text-justify w-responsive mx-auto m-3>

                    <h4 class=" h4 font-weight-bold pb-4 text-center shadow z-depth-5"> Application of partial derivatives</h4>
                    <br />
                    <br />
                    <p class="font-weight-bold text-center">
                        MS202<br/>
                        Marginal productivity (Cobb-Douglas)
                    </p>
                    <br/>
                    <p class="text-justify size20 red-text bg-grey-lighten-4">
                        Cobb-Douglas function
                    </p>
                   

                    <p class="blue-text">What is Cobb-Douglas equation?</p>
                    <div class="note note-primary shadow rounded border border-light z-depth-5">
                        <p class="ml-3 mr-3">
                            In economics, the Cobb-Douglas function is a  production function,
                            used to represent relationship between the amounts of two or more
                            inputs (particularly physical <strong>capital</strong> and <strong>labour</strong>)
                            and the amount of output that can be produced by those inputs.
                        </p>
                    </div>
                    <br />
                    <br />
                    <div>
                        In its most standard form for production of a single good with two factors,
                        the function is
                        <div v-katex:display="'f(x,y) = Ax^\\beta y^\\alpha '"></div>
                        <div>
                        -<span v-katex="'f (x,y)'"></span> is the total production<br/>
                        -<span v-katex="'x'"></span>  is the quantity of labour.<br/>
                        -<span v-katex="'y'"></span> is the quantity of capital.<br/>
                        -<span v-katex="'A'"></span> is a positive constant.<br/>
                        -<span v-katex="'\\beta'"></span> and <span v-katex="'\\alpha'"></span> are constants between 0 and 1.
                        </div>


                    </div>
                    <br />
                    <br/>
                    <p class="text-justify size20 red-text bg-grey-lighten-4">
                        Marginal Productivity
                    </p>
                    
                    
                    <p class="blue-text">What is marginal product?</p>
                    <div class="note note-primary shadow rounded border border-light z-depth-5">
                        <p class="ml-3 mr-3">
                            Marginal product is the change in total production, when there is an
                            infinitesimal change in the inputs. Marginal product is the first derivative
                            of the production function with respect to an input. The term <em>marginal</em> is
                            used because it measures the change of production with a small change of
                            either the capital or labour
                        </p>
                    </div>
                    <br/>
                    <br />
                    <div>
                        <p>
                            The marginal product of labour is defined as
                        </p>
                        <div v-katex:display="'\\frac{\\partial f}{\\partial x} '"></div>
                    </div>
                    <p>
                        and it measures the change of production with a small change of labour
                        Similarly, the marginal product of capital is defined as
                    </p>
                    <div v-katex:display="'\\frac{\\partial f}{\\partial y} '"></div>
                    <p>
                        and it measures the change of production with a small change of capital.
                    </p>
                    <br />
                    <div>
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Example on marginal productivity
                        </p>
                        <!--Example 1-->
                        <p class="green-text">Example (1)</p>
                        <p>
                            A certain country's production is described by the function
                        </p>
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'f(x,y)= \\space'"></span><span v-katex="example1Function"></span>
                        </div>
                        
                        units, when <span v-katex="'x'"></span> units of labour and <span v-katex="'y'"></span> units of capital were used
                        <br /><br />

                        <ul style="list-style-type:lower-alpha;">

                            <li>
                                What is the marginal productivity of labour and the marginal
                                productivity of capital when the amounts spent on labour and capital are
                                81 units and 625 units,respectively?
                            </li>
                            <li>
                                Should the government prioritise capital investment over increased
                                spending on labour at this time in order enhance the country's
                                productivity?
                            </li>
                        </ul>
                        <br />
                        <br />
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Finding marginal productivity of labour
                        </p>

                        <p>
                            The marginal productivity of labour when the amounts spent on labour
                            and capital are <span v-katex="'x'"></span> and <span v-katex="'y'"></span> units, respectively, is computed from the partial
                            derivative of <span v-katex="'f'"></span> with respect to <span v-katex="' x'"></span>  as
                        </p>
                        
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'\\frac{\\partial f}{\\partial x}=f_{x}(x,y)= \\space'"></span><span v-katex="fxFunction"></span>
                        </div>
                        <p>
                            When <span v-katex="'x = 81 '"></span> and <span v-katex="'y = 625'"></span> the required marginal productivity of labour is
                        </p>
                        <div v-katex:display="'f_x(81, 625) = 400\\left(\\frac{625}{81}\\right)^{\\frac{3}{4}} = 400\\left(\\frac{125}{27}\\right)^{\\frac{3}{4}} =  1851.85'"></div>
                        <p>
                            The marginal productivity of labour is 1851.85 units per unit increase in
                            labour expenditure (with capital expenditure held fixed at 625 units).
                        </p>
                    </div>
                    <br />
                    <br/>
                    <div>
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Finding marginal productivity of capital
                        </p>

                        <p>
                            The marginal productivity of capital when the amounts spent on labour
                            and capital are <span v-katex="'x'"></span>  and <span v-katex="'y'"></span>  units, respectively,
                            is computed from the partial derivative of <span v-katex="'f'"></span>  with respect to <span v-katex="'y'"></span>  as
                        </p>
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'\\frac{\\partial f}{\\partial y}=f_{y}(x,y)= \\space'"></span><span v-katex="fyFunction"></span>
                        </div>
                        <p>
                            When <span v-katex="'x = 81 '"></span> and <span v-katex="'y = 625'"></span> the required marginal productivity of capital is
                        </p>
                        <div v-katex:display="'f_y(81, 625) = 1200\\left(\\frac{81}{625}\\right)^{\\frac{1}{4}} = 1200\\left(\\frac{3}{5}\\right)^{\\frac{1}{4}} = 720'"></div>
                        <p>
                            The marginal productivity of capital is 720 units per unit increase in capital expenditure (with labour expenditure held fixed at 81 units).
                        </p>
                        <br /><br />
                        <div>
                            <p class="text-justify size20 red-text bg-grey-lighten-4">
                                Concluding from results
                            </p>
                            The results are
                            <p class="ml-5">
                                Marginal productivity of labour = 1851.85<br />
                                Marginal productivity of capital = 720
                            </p>
                            The results indicate that a unit increase in labour expenditure results in a
                            greater increase in productivity than a unit increase in capital expenditure
                            would have.<br />

                            <p>
                                Therefore, the government can be advised to spend
                                more on labour rather than on capital.
                            </p>

                        </div>
                    </div>
                </mdb-col>
            </mdb-row>
        </section>   
        <!--THE  END OF PARTIAL DERIVATIVES-->
    </mdb-container>
</template>
<script>
    import 'katex/dist/katex.min.css';
    import katex from 'katex/dist/katex.mjs'; 

    import nerdamer from 'nerdamer/nerdamer.core.js'
    import 'nerdamer/Algebra.js'
    import 'nerdamer/Calculus.js'
    import 'nerdamer/Solve.js'

    import { mdbContainer, mdbRow, mdbCol, mdbIcon } from "mdbvue";


    export default {
        name: "HelloWorld",
        components: {
            mdbContainer,
            mdbRow,
            mdbCol,
            mdbIcon
        },
        data() {
            return {
                answer: undefined,
                working: undefined,
                example1Function: undefined,
                fxFunction: undefined,
                fyFunction: undefined,
                answerVisibility: { visibility: false },
                workingVisibility: { visibility: false }
            }
        },
        beforeMount() {
            let initilizerVariable = this.generateRandomFunction();
            //this.example1Function = this.createFunction();
            this.example1Function = initilizerVariable[0];
            this.fxFunction = initilizerVariable[1];
            this.fyFunction = initilizerVariable[2];
            this.answer = this.unconstrainedSolution()[1];
            this.working = this.unconstrainedSolution()[0]

        },
        methods: {
            removeAsterix() {
            },
            update_element(element, value) {
                katex.render(value, this.$refs[`${element}`], {
                    throwOnError: false
                });
            },
            //Get random integer between min and max
            generateRandomInteger(min, max) {
                return Math.floor(min + Math.random() * (max + 1 - min))
            },
            isInt(num) {
                if (typeof num !== 'number')
                    return false;
                return !isNaN(num) &&
                    parseInt(Number(num)) == num &&
                    !isNaN(parseInt(num, 10));
            },
            plusOrMinus(nn) {
                let str = ' ';
                if (nn === 1) {
                    str = ` + `;
                }
                else if (nn === -1) {
                    str = ` - `;
                }
                else if (nn > 0) {
                    str = ` + ` + Math.abs(nn);
                } else {
                    str = ` - ` + Math.abs(nn);
                }
                return str
            },
            plusOrMinusNew(nn) {
                let str = ' ';
                if (nn === 1) {
                    str = `  `;
                }
                else if (nn === -1) {
                    str = ` - `;
                }
                else if (nn > 0) {
                    str = `  ` + Math.abs(nn);
                } else {
                    str = ` - ` + Math.abs(nn);
                }
                return str
            },

            plusOrMinusForEquation(nn, varx) {
                let str = ``;

                if (nn === 1) {
                    str = ` + ` + varx;
                }
                else if (nn === -1) {
                    str = ` - ` + varx;
                }
                else if (nn > 0) {
                    str = ` + ` + Math.abs(nn) + varx;
                }
                else if (nn < 0) {
                    str = ` - ` + Math.abs(nn) + varx;
                } else {
                    str = ` `
                }

                return str
            },
            isOdd(num) {
                if (typeof num === 'number') {
                    return ((num % 2) === 1) || ((num % 2) === -1) ? true : false;
                }
                else {
                    throw 'Not a number';
                }
            },
            generateCubic() {
                //f = x^3 + y^3  - (3/2)(a+b)x^2 - (3/2)*(C+d)y^2 + 3*a*b*x + 3*c*d*y + K;
                let a = this.generateRandomInteger(-9, 9);
                let b = this.generateRandomInteger(-9, 9);
                let c = this.generateRandomInteger(-9, 9);
                let d = this.generateRandomInteger(-9, 9);
                let K = a + b + c + d;

                let ax = -(3 / 2) * (a + b);
                let ay = -(3 / 2) * (c + d);
                while (!this.isOdd(ax) || !this.isOdd(ay)) {
                    a = this.generateRandomInteger(-9, 9);
                    b = this.generateRandomInteger(-9, 9);
                    c = this.generateRandomInteger(-9, 9);
                    d = this.generateRandomInteger(-9, 9);
                    K = this.generateRandomInteger(-20, 20);
                    ax = -(3 / 2) * (a + b);
                    ay = -(3 / 2) * (c + d);
                }

                return `x^3  +   y^3  ${this.plusOrMinusForEquation(ax, 'x^2')}  ${this.plusOrMinusForEquation(ay, 'y^2')}  ${this.plusOrMinusForEquation(3 * a * b, 'x')}  ${this.plusOrMinusForEquation(3 * c * d, 'y')}  ${this.plusOrMinus(K)}`

            },
            generateQuadratic(typed) {
                //f = a*x^2 + b*y^2  + c*x + d*y + K;
                // this.ex1.problemType = typed;
                let typeNum = typed;
                let x = 1;
                let y = 1;
                let a = 1;
                let b = 1;
                let c = 1;
                let d = 1;
                let e = 1;
                if (typeNum == "Maximum") {
                    //Maximum with f_{xx} < 0   
                    a = this.generateRandomInteger(-5, -1);
                    b = this.generateRandomInteger(-5, -1);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    c = -2 * a * x;
                    d = -2 * b * y;
                    e = this.generateRandomInteger(20, 100);
                    
                } else if (typeNum == "Minimum") {
                    // Minimum with f_{xx} > 0
                    a = this.generateRandomInteger(1, 5);
                    b = this.generateRandomInteger(1, 5);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    c = -2 * a * x;
                    d = -2 * b * y;
                    e = this.generateRandomInteger(20, 100);
                   
                } else {
                    //Opposite signs    
                    a = this.generateRandomInteger(-5, -1);
                    b = this.generateRandomInteger(1, 5);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    c = -2 * a * x;
                    d = -2 * b * y;
                    e = this.generateRandomInteger(20, 100);
                    
                }
                return `${this.plusOrMinusNew(a)}x^2   ${this.plusOrMinus(b)}y^2  ${this.plusOrMinus(c)}x  ${this.plusOrMinus(d)}y  ${this.plusOrMinus(e)}`


            },

            generateQuadratic2(typed) {
                //f = a*x^2 + b*y^2 + c*x + d*y + K*x*y + e;
                // this.ex2.problemType = typed;
                let typeNum = typed;
                let x = 1;
                let y = 1;
                let a = 1;
                let b = 1;
                let c = 1;
                let d = 1;
                let e = 1;
                
                let K = 1;
                
                let discriminant = 0;
                if (typeNum == "Maximum2") {
                    //Maximum with f_{xx} < 0   
                    a = this.generateRandomInteger(-5, -1);
                    b = this.generateRandomInteger(-5, -1);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    K = this.generateRandomInteger(1, 5);
                    c = -2 * a * x - K * y;
                    d = -2 * b * y - K * x;
                    e = this.generateRandomInteger(20, 100);
                   
                    discriminant = 1
                    while (discriminant <= 0) {
                        a = this.generateRandomInteger(-5, -1);
                        b = this.generateRandomInteger(-5, -1);
                        x = this.generateRandomInteger(1, 8);
                        y = this.generateRandomInteger(1, 9);
                        K = this.generateRandomInteger(1, 5);
                        c = -2 * a * x - K * y;
                        d = -2 * b * y - K * x;
                        e = this.generateRandomInteger(20, 100);
                       
                        discriminant = 4 * a * b - K * K
                    }
                } else if (typeNum == "Minimum2") {
                    // Minimum with f_{xx} > 0
                    a = this.generateRandomInteger(1, 5);
                    b = this.generateRandomInteger(1, 5);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    K = this.generateRandomInteger(1, 5);
                    c = -2 * a * x - K * y;
                    d = -2 * b * y - K * x;
                    e = this.generateRandomInteger(20, 100);
                   
                    discriminant = 1
                    while (discriminant <= 0) {
                        a = this.generateRandomInteger(-5, -1);
                        b = this.generateRandomInteger(-5, -1);
                        x = this.generateRandomInteger(1, 8);
                        y = this.generateRandomInteger(1, 9);
                        K = this.generateRandomInteger(1, 5);
                        c = -2 * a * x - K * y;
                        d = -2 * b * y - K * x;
                        e = this.generateRandomInteger(20, 100);
                        
                        discriminant = 4 * a * b - K * K
                    }
                } else {
                    //Opposite signs    
                    a = this.generateRandomInteger(-5, -1);
                    b = this.generateRandomInteger(1, 5);
                    x = this.generateRandomInteger(1, 8);
                    y = this.generateRandomInteger(1, 9);
                    K = this.generateRandomInteger(1, 5);
                    c = -2 * a * x - K * y;
                    d = -2 * b * y - K * x;
                    e = this.generateRandomInteger(20, 100);
                    
                    discriminant = 1
                    while (discriminant >= 0) {
                        a = this.generateRandomInteger(-5, -1);
                        b = this.generateRandomInteger(-5, -1);
                        x = this.generateRandomInteger(1, 8);
                        y = this.generateRandomInteger(1, 9);
                        K = this.generateRandomInteger(1, 5);
                        c = -2 * a * x - K * y;
                        d = -2 * b * y - K * x;
                        e = this.generateRandomInteger(20, 100);
                      
                        discriminant = 4 * a * b - K * K
                    }
                }
                //return   `${this.plusOrMinusNew(a)}x^2   ${this.plusOrMinus(b)}y^2  ${this.plusOrMinus(K)}*x*y  ${this.plusOrMinus(c)}x  ${this.plusOrMinus(d)}y  ${this.plusOrMinus(e)}`
                return `${this.plusOrMinusNew(e)}x^${this.plusOrMinusNew(a)}   ${this.plusOrMinusForEquation(b, 'y^2')}  ${this.plusOrMinusForEquation(K, 'x*y')}  ${this.plusOrMinusForEquation(c, 'x')}  ${this.plusOrMinusForEquation(d, 'y')}  ${this.plusOrMinus(e)}`

            },

            generateRandomFunction() {

                let A = this.generateRandomInteger(1500, 2500);
               // let B = this.generateRandomInteger(70, 85);
                //let C = this.generateRandomInteger(600, 650);
                let w = Math.random();
                let k = Math.random();

                let f = `${A}x^{${w}}y^{${k}}`;
                let fx = `${A}(${w})x^{${w - 1}}*y^{${k}}`;
                let fy = `${A}x^{${w}}*(${k})y^{${k-1}}`;
                let fxAnswer = nerdamer(`diff(${f},x)`);
                let fyAnswer = nerdamer(`diff(${f},y)`);

                return [f, fx, fy, fxAnswer, fyAnswer];
            },
            
            generateRevenueCost() {
                //  f = a*x^2 + b*y^2 + c*x + d*y + K*x*y + e;
                //  Maximum with f_{xx} < 0   
                let a = this.generateRandomInteger(-5, -1);
                let b = this.generateRandomInteger(-5, -1);
                let x = this.generateRandomInteger(20, 80);
                let y = this.generateRandomInteger(20, 80);
                let k1 = this.generateRandomInteger(1, 5);
                let R1 = -2 * a * x - k1 * y;
                let R2 = - k1 * x - 2 * b * y;
                let discriminant = 4 * a * b - k1 * k1
                while (discriminant <= 0) {
                    a = this.generateRandomInteger(-5, -1);
                    b = this.generateRandomInteger(-5, -1);
                    x = this.generateRandomInteger(20, 80);
                    y = this.generateRandomInteger(20, 80);
                    k1 = this.generateRandomInteger(1, 5);
                    R1 = -2 * a * x - k1 * y;
                    R2 = - k1 * x - 2 * b * y;
                    discriminant = 4 * a * b - k1 * k1
                }
                let n = this.generateRandomInteger(1, 6)
                let m = this.generateRandomInteger(1, 6)
                let K = a * x ^ 2 + b * y ^ 2 + k1 * x * y + R1 * x + R2 * y - this.generateRandomInteger(10000, 50000);
                // Rev = (a)*x^2  + (b)*y^2  + k1*x*y + (R1 + 5*n)*x + ( R2 + 5*m)*y ;
                // Cost = 5*n*x + 5*m*y + Round[K, 100];
                let e = Math.ceil(K / 100) * 100

                let maxProfit = a * x ^ 2 + b * y ^ 2 + k1 * x * y + R1 * x + R2 * y + e
                while (maxProfit <= 0) {
                    K = a * x ^ 2 + b * y ^ 2 + k1 * x * y + R1 * x + R2 * y - this.generateRandomInteger(5000, 20000);
                    // Rev = (a)*x^2  + (b)*y^2  + k1*x*y + (R1 + 5*n)*x + ( R2 + 5*m)*y ;
                    // Cost = 5*n*x + 5*m*y + Round[K, 100];
                    e = Math.ceil(K / 1000) * 1000
                    maxProfit = a * x ^ 2 + b * y ^ 2 + k1 * x * y + R1 * x + R2 * y + e
                }
                let Rev = `${this.plusOrMinusNew(a)}x^2   ${this.plusOrMinus(b)}y^2 ${this.plusOrMinusForEquation(k1, 'x*y')}  ${this.plusOrMinus(R1 + 5 * n)}x  ${this.plusOrMinus(R2 + 5 * m)}y`
                let Cost = `${this.plusOrMinusNew(5 * n)}x  ${this.plusOrMinus(5 * m)}y  ${this.plusOrMinus(e)}`
                let Profit = `${this.plusOrMinusNew(a)}x^2   ${this.plusOrMinus(b)}y^2 ${this.plusOrMinusForEquation(k1, 'x*y')}  ${this.plusOrMinus(R1)}x  ${this.plusOrMinus(R2)}y  ${this.plusOrMinus(-e)}`

                return [Rev, Cost, Profit, x, y, maxProfit]


            },
            classificationOfExtremPoint(a, b, D, fxx) {
                if (D < 0) {
                    return `\\textrm{Since } D < 0 \\textrm{ at }  (${a},${b})\\textrm{, f has a saddle point at } (${a},${b})`;
                }
                else if (D == 0) {
                    return `\\textrm{Since } D = 0, \\textrm{ the test is inconclusive and f may either have a relative extremum or a saddle point at } (${a},${b})`;
                }
                //At this point D > 0; 
                else if (fxx < 0) {
                    return `\\textrm{Since } D > 0 \\textrm{ and } f_{xx} < 0 \\textrm{ at } (${a},${b}), \\textrm{ f has a local maximum point at } (${a},${b})`;
                }
                else {
                    return `\\textrm{Since } D > 0 \\textrm{ and } f_{xx} > 0 \\textrm{ at } (${a},${b}), \\textrm{ we conclude that f has a local minimum point at } (${a},${b})`;
                }
            },
            getFunction() {
                return this.example1Function;
            },
            createFunction() {
                //Come back here!
                //return `x^2 -4*x + 3*y^2-18*y+5`; 
                //  return  `x^3 + 3*x^2 + y^3 - 3*y^2 - 8`; 
                //let choice = ["Maximum", "Minimum", "Opposite"]; 
                let choice = ["Maximum2", "Minimum2", "Opposite"];
                let typeNum = choice[Math.floor(Math.random() * choice.length)];//Randomly choosing type 
                return this.generateQuadratic2(typeNum);
            },
            handleClickNewExample() {
                //   let choice = ["Maximum", "Minimum", "Opposite"]; 
               // let choice = ["Maximum2", "Minimum2", "Opposite"];
               // let typeNum = choice[Math.floor(Math.random() * choice.length)];//Randomly choosing type 
                //this.example1Function = this.generateQuadratic2(typeNum);
                this.example1Function = this.generateRandomFunction();
                this.answer = this.unconstrainedSolution()[1];
                this.working = this.unconstrainedSolution()[0];
                this.update_element('answer', this.answer);
                this.update_element('working', this.working);
                this.update_element('example1Function', this.example1Function);
                this.update_element('fxFunction', this.fxFunction);
                this.update_element('fyFunction', this.fyFunction);
            },

            unconstrainedSolution() {
                // NOTE THAT THIS VERSION ONLY APPLIES TO QUADRATIC NON-LINEARITY
                //let f = 'x^2 -4*x + 3*y^2-18*y+5'
                let f = this.example1Function;
                let fx = nerdamer(`diff(${f},x)`);
                let fy = nerdamer(`diff(${f},y)`);
                let fxx = nerdamer(`diff(${f},x,2)`);
                let fyy = nerdamer(`diff(${f},y,2)`);
                let fxy = nerdamer(`diff(${fx},y)`);

                let criticalPoints = nerdamer.solveEquations([`${fx} = 0`, `${fy} = 0`]);

                let var1 = { value: undefined, label: undefined };
                let var2 = { value: undefined, label: undefined };
                var1.label = criticalPoints[0][0];
                var1.value = criticalPoints[0][1];
                var2.label = criticalPoints[1][0];
                var2.value = criticalPoints[1][1];
                let fxxValue = fxx.sub(var1.label, var1.value).sub(var2.label, var2.value);
                let fyyValue = fyy.sub(var1.label, var1.value).sub(var2.label, var2.value);
                let fxyValue = fxy.sub(var1.label, var1.value).sub(var2.label, var2.value);

                let discriminant = fxxValue * fyyValue - fxyValue * fxyValue;

                let solutionText =
                    `\\textrm{We start by evaluating the derivatives and equating them to zero` +
                    `to find the critical points. This leads to}\\\\
      \\begin{aligned}
       f_x &=  ${fx.toTeX()}  = 0 \\\\     
       f_y &=  ${fy.toTeX()}  = 0 \\\\
    \\end{aligned}
    \\\\
    \\textrm{Solving the above equations gives } ${var1.label} = ${var1.value} \\textrm{ and }` +
                    `${var2.label} = ${var2.value} .\\\\` +
                    `\\textrm{The point } (${var1.value},${var2.value}) \\textrm{ is the critical point of }` +
                    `f(${var1.label},${var2.label})\\\\` +
                    `\\textrm{To classify the critical points, we evaluate the second derivatives and the discriminant }` +
                    `D .\\\\` + `\\textrm{ then we apply the second derivative test. The second derivatives are}\\\\` +
                    `\\begin{aligned}
        f_{xx} = ${fxx},\\quad f_{yy} = ${fyy}, \\textrm{ and } f_{xy} = ${fxy}.
        \\end{aligned}`
                    + `\\textrm{To compute the discriminant } D, \\textrm{ we note that}\\\\`
                    + `\\textrm{At } (${var1.label},${var2.label}): 
         f_{xx} = ${fxxValue},\\quad  f_{yy} = ${fyyValue}, \\textrm{ and } f_{xy} = ${fxy}.\\\\` +
                    `\\textrm{Thus, } D = f_{xx}f_{yy} - f_{xy}^2  = ${discriminant}`;

                //this.answer = solutionText
                return [solutionText, this.classificationOfExtremPoint(var1.value, var2.value, discriminant, fxxValue)];
            }

            
        }
    }
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



.headingUnd{
    border-bottom: 2px solid currentColor;
    display: inline-block;
    line-height: 0.85;
    text-shadow:
    2px 2px white,
    2px -2px white,
    -2px 2px white,
    -2px -2px white;
}
    .size20 {
        font-size:20px;
        
    }

    .bg-grey-lighten-4 {
        background-color:#f5f5f5;
    }


</style>