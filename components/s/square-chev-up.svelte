<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2dnpkjjq.css';
import '../../css/z/z456xsbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2dnpkjjq"/><path class="z456xsbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-chev-up" {...props}></Icon>
