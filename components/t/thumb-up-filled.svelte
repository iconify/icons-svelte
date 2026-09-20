<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m08qq3b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m08qq3b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:thumb-up-filled" {...props}></Icon>
