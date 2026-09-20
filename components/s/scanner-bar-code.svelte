<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6c-fwi1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y6c-fwi1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:scanner-bar-code" {...props}></Icon>
