<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj5ssyykk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":224};
const content = `<path class="rj5ssyykk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rust-light" {...props}></Icon>
