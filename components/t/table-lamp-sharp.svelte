<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap48v56cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:table-lamp-sharp" {...props}></Icon>
<style>
:global(.ap48v56cb) {
  fill: currentColor;
  d: path("M13 21v-2h8v2zm3-3V7h-5v4H2.475l3.5-8H11v2h7v13z");
}

</style>
