<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7_3dwbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7_3dwbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:row-height-s-outline" {...props}></Icon>
