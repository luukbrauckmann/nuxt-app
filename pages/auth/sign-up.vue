<template>
    <main>
        <h1>Sign Up</h1>
    
        <form class="form" action="/api/auth/sign-up" method="POST">
    
            <div class="form__field">
                <label for="email">Email</label>
                <input type="email" name="email" autocomplete="email" required />
            </div>
    
            <div class="form__field">
                <label for="password">Password</label>
                <input type="password" name="password" autocomplete="current-password" required />
            </div>
    
            <div class="form__field">
                <button type="submit">Sign Up</button>
            </div>
        </form>

        <NuxtLink to="/auth/sign-in">Already have an account? Sign In.</NuxtLink>
    </main>
</template>