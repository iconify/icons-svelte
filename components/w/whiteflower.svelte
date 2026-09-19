<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1oj3o3gm.css';
import '../../css/h/hy2vl0dwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1oj3o3gm"/><path class="hy2vl0dwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whiteflower" {...props}></Icon>
