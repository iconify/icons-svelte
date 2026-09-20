<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av8ob7b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="av8ob7b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:volume-outline" {...props}></Icon>
