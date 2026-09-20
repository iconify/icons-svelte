<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dht-ux8xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dht-ux8xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sponsor-tiers-16" {...props}></Icon>
