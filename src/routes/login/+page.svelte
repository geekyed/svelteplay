<div class='flex justify-center flex-col items-center'>
  <form class='flex flex-col justify-center items-center gap-2 m-10'>
    <input type="text" id='email' placeholder='email' class='rounded border border-gray-700 px-2'/>
    <input type="password" id='password' placeholder='password' class='rounded border border-gray-700 px-2'/>
    <button class='bg-teal-700 text-white rounded w-min px-5'on:click={login}>Login</button>
  </form>
  <div class='flex justify-center items-center'>
    <button class='rounded border-2 border-black w-max px-5'on:click={loginGoogle}>Login with Google</button>
  </div>
</div>


<script>
  const loginGoogle = () => console.log('login with google clicked')
  const login = () => console.log('login clicked')
</script>