<h1>sign up!!</h1>

<div class="container mx-auto">
    <form id="form">
        <div class="join join-vertical">
            <div class="form-control">
                <label class="label">
                    <span class="label-text">What is your email?</span>
                </label>
                <input
                    type="text"
                    placeholder="example@chessisfun.com"
                    class="input input-bordered"
                />
                <label class="label">
                    <span class="label-text">What is your phone number?</span>
                </label>
                <input
                    type="tel"
                    placeholder="111-111-1111"
                    pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"
                    class="input input-bordered w-full max-w-xs"
                    required
                />
                <label class="label">
                    <span class="label-text"
                        >What are your available hours?</span
                    >
                </label>
                <input
                    type="text"
                    placeholder="example@chessisfun.com"
                    class="input input-bordered w-full max-w-xs"
                />

                <button class="btn" type="submit">Submit</button>
            </div>
        </div>
    </form>
</div>

<style>
    #form {
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>
