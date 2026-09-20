<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1sfr-bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w1sfr-bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:square-outline" {...props}></Icon>
