<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-ek1u2sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-ek1u2sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-interface" {...props}></Icon>
