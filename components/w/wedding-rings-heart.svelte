<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt0yh_b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0yh_b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wedding-rings-heart" {...props}></Icon>
