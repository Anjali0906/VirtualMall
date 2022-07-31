<div id="profile_item_details">
	<div id="profile_item_name">Item Name</div>
	<div class="item">Rs <span id="profile_item_price">Item Price </span></div>
	<div id="profile_item_desc" class="item">
		
		<br /> 
	</div>
</div>

<style>
	#profile_item_details {
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;

		height: 22%;

		padding: var(--pad);

		pointer-events: auto;
	}

	@media screen and (min-width: 800px) {
		#profile_item_details {
			padding: var(--pad2);
		}
	}

	.item {
		font-size: 1.5rem;
	}
</style>
