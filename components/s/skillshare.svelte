<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcaca32fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcaca32fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:skillshare" {...props}></Icon>
