<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoki9_bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qoki9_bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:view-stream" {...props}></Icon>
