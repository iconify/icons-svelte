<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g68p0v7pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g68p0v7pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signage-4" {...props}></Icon>
