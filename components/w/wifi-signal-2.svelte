<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p95zaibmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p95zaibmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wifi-signal-2" {...props}></Icon>
