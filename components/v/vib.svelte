<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8n6gwang"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vib" {...props}></Icon>
<style>
:global(.p8n6gwang) {
  fill: var(--svg-color--ff1e43, #ff1e43);
  d: path("M8.143 3H4.607l10.286 18h4.5V3h-3.214v13.822z");
}

</style>
