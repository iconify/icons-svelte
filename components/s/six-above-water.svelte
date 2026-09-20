<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw6abvbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mw6abvbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:six-above-water" {...props}></Icon>
