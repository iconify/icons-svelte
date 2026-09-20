<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ih2lb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5ih2lb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-portrayal-outline" {...props}></Icon>
