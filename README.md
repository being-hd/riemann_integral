```html
<!DOCTYPE html>
<html>
<head>
    <title>Computing Riemann Integral</title>
</head>
<body>
    <p>A Python implementation of the Riemann Integral using first principles.</p>

    <h2>Example:</h2>
    <pre><code>
    obj = riemann_integral('x^2', 0, 1)
    obj.integral_value()
    </code></pre>

    <h3>Output:</h3>
    <pre><code>
    Upper sum U(f, 500) = 0.334334
    Lower sum L(f, 500) = 0.332334
    Integral is: 0.333334
    </code></pre>

    <p>Here, the number of partition points (n) is 500.</p>
</body>
</html>
