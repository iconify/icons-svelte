<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csg1b869a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="csg1b869a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:toggle-on" {...props}></Icon>
