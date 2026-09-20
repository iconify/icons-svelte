<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u70bgjs_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u70bgjs_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:swap-left-right" {...props}></Icon>
