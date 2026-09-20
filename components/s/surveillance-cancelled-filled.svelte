<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg994ldbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg994ldbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:surveillance-cancelled-filled" {...props}></Icon>
