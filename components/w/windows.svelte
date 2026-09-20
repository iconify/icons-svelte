<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw-vxn9lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jw-vxn9lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:windows" {...props}></Icon>
