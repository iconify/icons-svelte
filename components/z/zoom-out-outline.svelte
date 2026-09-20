<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkx9g0b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wkx9g0b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:zoom-out-outline" {...props}></Icon>
