<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd39qiwhy.css';
import '../../css/i/iwqrvp1ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd39qiwhy"/><path class="iwqrvp1ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-up-bold-duotone" {...props}></Icon>
