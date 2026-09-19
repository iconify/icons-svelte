<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul8cvla7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8cvla7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:swatchbook-solid" {...props}></Icon>
