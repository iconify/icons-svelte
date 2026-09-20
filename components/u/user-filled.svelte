<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyw10oeoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyw10oeoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-filled" {...props}></Icon>
