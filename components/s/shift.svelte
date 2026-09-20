<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzpy4zb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gzpy4zb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shift" {...props}></Icon>
