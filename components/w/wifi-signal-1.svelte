<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f06gerbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f06gerbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wifi-signal-1" {...props}></Icon>
