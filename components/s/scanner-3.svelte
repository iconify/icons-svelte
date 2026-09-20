<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umo3nacfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="umo3nacfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:scanner-3" {...props}></Icon>
