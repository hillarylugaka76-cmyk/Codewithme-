
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#0f0f0f">

<title>AdSelect - Sign Up</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    min-height: 100vh;
    background: #0f0f0f;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    animation: fadeIn .8s ease;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.container {
    width: 100%;
    max-width: 900px;
    background: #fff;
    border-radius: 24px;
    display: flex;
    overflow: hidden;
    min-height: 560px;
    box-shadow: 0 20px 50px rgba(0,0,0,.5);
    animation: slideUp .7s ease;
}

@keyframes slideUp {
    from {
        opacity: 0;
        transform: translateY(35px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* LEFT SECTION */

.left {
    flex: 1;
    background: #FFD500;
    padding: 35px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
    overflow: hidden;
}

.left::after {
    content: "💛";
    position: absolute;
    right: -20px;
    bottom: -30px;
    font-size: 180px;
    opacity: .25;
    pointer-events: none;
}

.logo {
    font-size: 26px;
    font-weight: 900;
    color: #111;
}

.logo span {
    background: #111;
    color: #FFD500;
    padding: 2px 10px;
    border-radius: 8px;
}

.left h1 {
    font-size: 36px;
    line-height: 1.2;
    color: #111;
    margin-top: 30px;
}

.left h1 span {
    color: #fff;
    -webkit-text-stroke: 1px #111;
}

.left p {
    color: #333;
    font-size: 15px;
    margin-top: 12px;
    line-height: 1.6;
}

.features {
    margin-top: 25px;
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.feature {
    background: #111;
    color: white;
    padding: 12px 15px;
    border-radius: 12px;
    display: flex;
    gap: 10px;
    align-items: center;
    font-size: 14px;
}

.feature b {
    color: #FFD500;
}

.bottom {
    font-size: 12px;
    color: #555;
    margin-top: 20px;
}

/* RIGHT SECTION */

.right {
    flex: 1;
    padding: 35px;
    background: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.right h2 {
    font-size: 26px;
    color: #111;
}

.right h2 span {
    color: #E6B800;
}

.sub {
    color: #777;
    font-size: 14px;
    margin: 6px 0 20px;
}

label {
    font-size: 13px;
    font-weight: 700;
    color: #333;
    display: block;
    margin-bottom: 6px;
}

.row {
    display: flex;
    gap: 12px;
}

.row div {
    flex: 1;
    min-width: 0;
}

input {
    width: 100%;
    padding: 13px 14px;
    margin-bottom: 14px;
    border: 2px solid #eee;
    border-radius: 12px;
    outline: none;
    font-size: 14px;
    background: #fafafa;
    transition: .3s;
}

input:focus {
    border-color: #FFD500;
    background: #fff;
    box-shadow: 0 0 0 3px rgba(255,213,0,.2);
}

.terms {
    font-size: 12px;
    color: #888;
    margin: 2px 0 16px;
    line-height: 1.5;
}

.terms a {
    color: #111;
    font-weight: 700;
}

.btn {
    width: 100%;
    padding: 14px;
    border: none;
    border-radius: 12px;
    background: #111;
    color: #FFD500;
    font-size: 16px;
    font-weight: 800;
    cursor: pointer;
    transition: .3s;
}

.btn:hover {
    background: #FFD500;
    color: #111;
    box-shadow: 0 5px 15px rgba(255,213,0,.3);
    transform: translateY(-2px);
}

.divider {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #aaa;
    font-size: 12px;
    margin: 18px 0;
}

.divider::before,
.divider::after {
    content: "";
    flex: 1;
    height: 1px;
    background: #eee;
}

.google {
    width: 100%;
    padding: 12px;
    border: 2px solid #eee;
    background: white;
    border-radius: 12px;
    cursor: pointer;
    font-weight: 700;
    font-size: 14px;
    transition: .3s;
}

.google:hover {
    border-color: #FFD500;
    background: #fffdf2;
}

.login {
    text-align: center;
    margin-top: 18px;
    font-size: 14px;
    color: #777;
}

.login a {
    color: #111;
    font-weight: 800;
    text-decoration: none;
}

.login a:hover {
    color: #d6a900;
}

/* MOBILE RESPONSIVENESS */

@media(max-width: 700px) {
    body {
        padding: 12px;
    }

    .container {
        flex-direction: column;
    }

    .left {
        padding: 25px;
        min-height: 230px;
    }

    .left h1 {
        font-size: 28px;
        margin-top: 20px;
    }

    .features {
        display: none;
    }

    .right {
        padding: 25px;
    }
}

@media(max-width: 380px) {
    .row {
        flex-direction: column;
        gap: 0;
    }

    .right h2 {
        font-size: 22px;
    }
}
</style>
</head>

<body>

<div class="container">

    <!-- LEFT SECTION -->

    <section class="left">

        <div>
            <div class="logo">
                AD<span>SELECT</span>
            </div>

            <h1>
                Your Ads.<br>
                <span>Your Audience.</span><br>
                Your Earnings.
            </h1>

            <p>
                Join creators and advertisers growing
                with AdSelect every day.
            </p>

            <div class="features">

                <div class="feature">
                    💰 <span><b>Fast Payouts</b> — Timely payments</span>
                </div>

                <div class="feature">
                    📊 <span><b>Real Analytics</b> — Track performance</span>
                </div>

                <div class="feature">
                    🛡️ <span><b>100% Safe</b> — Verified advertising</span>
                </div>

            </div>
        </div>

        <div class="bottom">
            © 2026 AdSelect. All rights reserved.
        </div>

    </section>

    <!-- RIGHT SECTION -->

    <section class="right">

        <h2>
            Create your <span>AdSelect</span> account
        </h2>

        <p class="sub">
            It takes less than 1 minute to join.
        </p>

        <form action="#" method="post">

            <div class="row">

                <div>
                    <label for="firstName">First Name</label>
                    <input
                        type="text"
                        id="firstName"
                        name="firstName"
                        placeholder="John"
                        autocomplete="given-name"
                        required>
                </div>

                <div>
                    <label for="lastName">Last Name</label>
                    <input
                        type="text"
                        id="lastName"
                        name="lastName"
                        placeholder="Doe"
                        autocomplete="family-name"
                        required>
                </div>

            </div>

            <label for="email">Email Address</label>
            <input
                type="email"
                id="email"
                name="email"
                placeholder="john@example.com"
                autocomplete="email"
                required>

            <label for="password">Password</label>
            <input
                type="password"
                id="password"
                name="password"
                placeholder="Create a strong password"
                minlength="8"
                autocomplete="new-password"
                required>

            <label for="confirmPassword">Confirm Password</label>
            <input
                type="password"
                id="confirmPassword"
                name="confirmPassword"
                placeholder="Confirm your password"
                minlength="8"
                autocomplete="new-password"
                required>

            <p class="terms">
                By signing up, you agree to AdSelect's
                <a href="terms.html">Terms</a> and
                <a href="privacy.html">Privacy Policy</a>.
            </p>

            <button type="submit" class="btn">
                Create Account →
            </button>

        </form>

        <div class="divider">
            OR CONTINUE WITH
        </div>

        <button type="button" class="google">
            🔍 Continue with Google
        </button>

        <div class="login">
            Already have an account?
            <a href="login.html">Log in</a>
        </div>

    </section>

</div>

</body>
</html>
