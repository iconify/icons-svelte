<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7m5x004v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n7m5x004v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-down-outline" {...props}></Icon>
