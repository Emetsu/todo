<script>import "../app.postcss";</script>

<main class="bg-gradient-to-br from-indigo-300 via-blue-600 to-cyan-300 h-screen">
    <nav class="fixed w-full flex justify-evenly text-black">
        <a class="" href="/">Homepage</a>
        <a class="" href="/about">About page</a>
        <a class="" href="/contact">Contact</a>
        <a class="" href="/account">Account</a>
        <a class="" href="/account/register">Register</a>
        <a class="" href="/account/login">Login</a>
        
   
    </nav>
    <slot />
</main>