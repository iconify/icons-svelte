<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abbymobak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abbymobak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:soonwithrightarrow" {...props}></Icon>
