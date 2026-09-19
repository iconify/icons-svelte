<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kttl0gagx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kttl0gagx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:swatchbook-outline" {...props}></Icon>
