<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9koci0im.css';
import '../../css/h/hoxqff5ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9koci0im"/><path class="hoxqff5ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:zoom-out" {...props}></Icon>
