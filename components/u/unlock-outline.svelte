<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvi86xbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rvi86xbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:unlock-outline" {...props}></Icon>
