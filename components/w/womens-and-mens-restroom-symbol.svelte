<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxg2fn1hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nxg2fn1hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:womens-and-mens-restroom-symbol" {...props}></Icon>
