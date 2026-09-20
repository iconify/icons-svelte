<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2zb1x5to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i2zb1x5to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-with-raised-hood" {...props}></Icon>
