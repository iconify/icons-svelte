<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct297rbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ct297rbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turnkey-linux" {...props}></Icon>
