<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ice71tbrt.css';
import '../../css/w/wl50x4lxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ice71tbrt"/><path class="wl50x4lxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:warning" {...props}></Icon>
