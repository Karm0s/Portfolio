<template>
	<nav class="flex justify-between items-center bg-blue-100 h-12 px-4">
		<div class="h-full">
			<div class="navlink">
				<NuxtLink to="/">Yanis B</NuxtLink>
			</div>
		</div>
		<div class="flex justify-between h-full">
			<div class="navlink">
				<NuxtLink to="/projects">projects</NuxtLink>
			</div>
			<div class="navlink">
				<NuxtLink to="/services">services</NuxtLink>
			</div>
			<div class="navlink">
				<NuxtLink to="/contact">contact</NuxtLink>
			</div>
		</div>
		<div class="h-full">
			<div class="navlink">
				<nuxtlink to="/">
					<Icon name="uil:github" color="black" class="text-2xl" />
				</nuxtlink>
				
			</div>
		</div>
	</nav>
</template>
<style lang="postcss">
.navlink {
	@apply flex w-28 h-full bg-red-100 text-center align-middle;
}
.navlink > * {
	@apply m-auto;
}
</style>
