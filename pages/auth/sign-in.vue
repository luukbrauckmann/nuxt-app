<template>
    <main>
        <h1>Sign In</h1>
    
        <form class="form" action="/api/auth/sign-in" method="POST">
    
            <div class="form__field">
                <label for="email">Email</label>
                <input type="email" name="email" autocomplete="email" required />
            </div>
    
            <div class="form__field">
                <label for="password">Password</label>
                <input type="password" name="password" autocomplete="current-password" required />
            </div>
    
            <div class="form__field">
                <button type="submit">Sign In</button>
            </div>
        </form>

        <NuxtLink to="/auth/sign-up">Sign Up</NuxtLink>
    </main>
</template>