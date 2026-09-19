<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhtg83bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhtg83bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:socks" {...props}></Icon>
