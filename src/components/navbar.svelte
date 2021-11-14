<script lang="ts">
</script>

<mwc-top-app-bar>
	<img
		class="sniper-profile"
		slot="navigationIcon"
		src="/assets/sniper-profile.png"
		alt="Sniper profile"
	/>

	<div slot="title">Sniper</div>
	<mwc-icon-button class="profile-button" slot="actionItems" icon="person" />
</mwc-top-app-bar>

<style lang="scss">
	.sniper-profile {
		width: 48px;
		height: 48px;
		border-radius: 50%;
	}
	.profile-button {
		--mdc-icon-size: 40px;
	}
</style>
