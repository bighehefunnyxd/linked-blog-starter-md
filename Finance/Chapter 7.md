
### Present Value Interest Factor of Annuity (PVIFA)

The PVIFA is used to calculate the present value of a series of annuity payments. The formula is:
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi>P</mi><mi>V</mi><mi>I</mi><mi>F</mi><mi>A</mi><mo stretchy="false">(</mo><mi>r</mi><mo separator="true">,</mo><mi>n</mi><mo stretchy="false">)</mo><mo>=</mo><mfrac><mrow><mn>1</mn><mo>−</mo><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><msup><mo stretchy="false">)</mo><mrow><mo>−</mo><mi>n</mi></mrow></msup></mrow><mi>r</mi></mfrac></mrow><annotation encoding="application/x-tex">PVIFA(r, n) = \frac{1 - (1 + r)^{-n}}{r}
</annotation></semantics></math>
### Present Value Interest Factor (PVIF)

The PVIF is used to calculate the present value of a single future sum of money. The formula is:

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi>P</mi><mi>V</mi><mi>I</mi><mi>F</mi><mo stretchy="false">(</mo><mi>r</mi><mo separator="true">,</mo><mi>n</mi><mo stretchy="false">)</mo><mo>=</mo><mfrac><mn>1</mn><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><msup><mo stretchy="false">)</mo><mi>n</mi></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">PVIF(r, n) = \frac{1}{(1 + r)^n}
</annotation></semantics></math>
### Current Yield

The *current yield* is calculated as the annual coupon payment divided by the current price of the bond:
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mtext>Current&nbsp;Yield</mtext><mo>=</mo><mfrac><mtext>Annual&nbsp;Coupon&nbsp;Payment</mtext><mtext>Current&nbsp;Price</mtext></mfrac><mo>=</mo><mfrac><mn>106</mn><mn>1081</mn></mfrac><mo>≈</mo><mn>9.81</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">\text{Current Yield} = \frac{\text{Annual Coupon Payment}}{\text{Current Price}} = \frac{106}{1081} \approx 9.81\%
</annotation></semantics></math>

### Yield to Maturity (YTM) and Current Bond Price

The *YTM* is the interest rate that equates the present value of the bond’s cash flows to its current price. This requires solving the following *Current Bond Price* equation, typically using a financial calculator or iterative methods:
for semiannual:
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi>P</mi><mo>=</mo><munderover><mo>∑</mo><mrow><mi>t</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mfrac><mi>C</mi><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><mi mathvariant="normal">/</mi><mn>2</mn><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>t</mi></mrow></msup></mrow></mfrac><mo>+</mo><mfrac><mi>F</mi><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><mi mathvariant="normal">/</mi><mn>2</mn><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>n</mi></mrow></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">P = \sum_{t=1}^{n} \frac{C}{(1 + r/2)^{2t}} + \frac{F}{(1 + r/2)^{2n}}
</annotation></semantics></math>
or for annual:
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi>P</mi><mo>=</mo><mfrac><mrow><mi>C</mi><mo>×</mo><mo stretchy="false">(</mo><mn>1</mn><mo>−</mo><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><msup><mo stretchy="false">)</mo><mrow><mo>−</mo><mi>n</mi></mrow></msup><mo stretchy="false">)</mo></mrow><mi>r</mi></mfrac><mo>+</mo><mfrac><mi>F</mi><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mi>r</mi><msup><mo stretchy="false">)</mo><mi>n</mi></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">P = \frac{C \times (1 - (1 + r)^{-n})}{r} + \frac{F}{(1 + r)^n}
</annotation></semantics></math>

Where:

- (P) = Current price of the bond
	- % of face value, PV
- (C) = *Semiannual/annual* coupon payment
	- % of the face value per period, PMT
- (F) = Face value of the bond
	- FV of bond
- (r) = *Semiannual* YTM
- (n) = Number of *semiannual* periods
- $\sum_{t=1}^{n}$ is the apart of following following semiannual coupon payments (its basically the sum of the periods of n with t going up to n)


	<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mtext>Current&nbsp;Price&nbsp;of&nbsp;the&nbsp;Bond</mtext><mo>=</mo><munderover><mo>∑</mo><mrow><mi>t</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mfrac><mtext>Semiannual&nbsp;Coupon&nbsp;Payment</mtext><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mfrac><mtext>Semiannual&nbsp;YTM</mtext><mn>2</mn></mfrac><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>t</mi></mrow></msup></mrow></mfrac><mo>+</mo><mfrac><mtext>Face&nbsp;Value</mtext><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mfrac><mtext>Semiannual&nbsp;YTM</mtext><mn>2</mn></mfrac><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>n</mi></mrow></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">\text{Current Price of the Bond} = \sum_{t=1}^{n} \frac{\text{Semiannual Coupon Payment}}{(1 + \frac{\text{Semiannual YTM}}{2})^{2t}} + \frac{\text{Face Value}}{(1 + \frac{\text{Semiannual YTM}}{2})^{2n}}
</annotation></semantics></math>


Current Price = PVIFA + PVIF
*present value of the coupon payments (**PVIFA**):*
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><munderover><mo>∑</mo><mrow><mi>t</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mfrac><mtext>Semiannual&nbsp;Coupon&nbsp;Payment</mtext><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mfrac><mtext>Semiannual&nbsp;YTM</mtext><mn>2</mn></mfrac><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>t</mi></mrow></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">\sum_{t=1}^{n} \frac{\text{Semiannual Coupon Payment}}{(1 + \frac{\text{Semiannual YTM}}{2})^{2t}}
</annotation></semantics></math>
 *present value of the face value (**PVIF**):*
 <math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mfrac><mtext>Face&nbsp;Value</mtext><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mfrac><mtext>Semiannual&nbsp;YTM</mtext><mn>2</mn></mfrac><msup><mo stretchy="false">)</mo><mrow><mn>2</mn><mi>n</mi></mrow></msup></mrow></mfrac></mrow><annotation encoding="application/x-tex">\frac{\text{Face Value}}{(1 + \frac{\text{Semiannual YTM}}{2})^{2n}}
</annotation></semantics></math>
The syntax for the YTM:
	move the cursor to **I%** and press `[ALPHA]` `[ENTER]`. The calculator will display the semiannual YTM. To get the annual YTM, multiply the result by 2.
### Effective Annual Yield (EAY)

The *EAY* accounts for compounding within the year and is calculated as:

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mtext>EAY</mtext><mo>=</mo><mo stretchy="false">(</mo><mn>1</mn><mo>+</mo><mfrac><mtext>YTM</mtext><mn>2</mn></mfrac><msup><mo stretchy="false">)</mo><mn>2</mn></msup><mo>−</mo><mn>1</mn></mrow><annotation encoding="application/x-tex">\text{EAY} = (1 + \frac{\text{YTM}}{2})^2 - 1
</annotation></semantics></math>
The syntax for the effective annual yield
	`►Eff(` function is `►Eff(nominal rate, compounding periods)`





