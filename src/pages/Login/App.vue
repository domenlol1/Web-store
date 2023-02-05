<template>
    <h1>
        Log in
    </h1>
    <form>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>

        <button type="submit"><a href="index" class="a1">Continue</a></button>
    </form>
    <div class="text">
        <p>Don't have an account? <a href="signup" class="a2">Sign up</a></p>
    </div>
</template>

<script>
export default {
    data() {
        return {};
    }
}
</script>

<style scoped>
#app {
    margin: 0 auto;
    font-weight: normal;
    font-family: latoregular, Lato, sans-serif;
}

form {
    width: 300px;
    margin: 0 auto;
    margin-top: 20px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

label {
    display: block;
    margin-bottom: 10px;
}

input[type="email"],
input[type="password"] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button[type="submit"] {
    width: 100%;
    background-color: #1aaaaf;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #0a56bb;
}

.text {
    margin-top: 10px;
    text-align: center;
}
.a2 {
    text-decoration: none;
    --link-color: #1aaaaf;
    color: var(--link-color);
    margin-left: 5px;
}
h1 {
    text-align: center;
    margin-top: 80px;
}
.a1 {
    text-decoration: none;
    color: white;
}
</style>
