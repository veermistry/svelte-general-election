<script>
    import Nav from '../components/nav.svelte'
</script>
<main>
    <Nav/>
    <div class="pt-10 underline text-center text-red-300 text-xl">Unfortunately, registration ended April 1st.</div>
    <div class="page-wrapper px-5 pt-10 flex-col justify-center">
        <h1 class="text-center">Click <u><a href="https://www.votetexas.gov/register/index.html" target="_blank">here</a></u> to begin your registration process</h1>
        <b class="text-center" >Are you eligible to vote?</b>
        <span class="text-center block">You are eligible if:</span>
        <ul class="list-disc px-5 pt-2">
            <li>You are a United States citizen</li>
            <li>You are a resident of the county where you submit the application</li>
            <li>You are at least 17 years and 10 months old, and you are 18 years of age on Election Day</li>
            <li>You are not a convicted felon (you may be eligible to vote if you have completed your sentence, probation, and parole); and</li>
            <li>You have not been declared by a court exercising probate jurisdiction to be either totally mentally incapacitated or partially mentally incapacitated without the right to vote</li>
        </ul>
        <small class="text-center">Information obtained and verified via <a href="https://www.votetexas.gov/register/index.html" class = "underline">https://www.votetexas.gov/register/index.html</a>
    </div>
</main>

<style global>

	main {
		max-width: 100vw;
		overflow-x: hidden;
	}

	.page-wrapper {
		max-width: 1920px;
		margin-left: auto;
		margin-right: auto;
	}
</style>

