<script lang="ts">
	import * as Drawer from '$lib/components/ui/drawer/index.js';
	import { Button, buttonVariants } from '$lib/components/ui/button/index.js';
</script>

<Drawer.Root>
	<Drawer.Trigger class={buttonVariants({ variant: 'default', class: "m-2"  })}>Open</Drawer.Trigger>
	<Drawer.Content>
		<Drawer.Header>
			<Drawer.Title>Are you sure absolutely sure?</Drawer.Title>
			<Drawer.Description>This action cannot be undone.</Drawer.Description>
		</Drawer.Header>
		<Drawer.Footer>
			<Button>Submit</Button>
			<Drawer.Close>Cancel</Drawer.Close>
		</Drawer.Footer>
	</Drawer.Content>
</Drawer.Root>
