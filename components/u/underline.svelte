<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsjr3bb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jsjr3bb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:underline" {...props}></Icon>
