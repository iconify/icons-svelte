<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfnwxgt6p.css';
import '../../css/c/c9p0p_5vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wfnwxgt6p"/><path class="c9p0p_5vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:trpc" {...props}></Icon>
