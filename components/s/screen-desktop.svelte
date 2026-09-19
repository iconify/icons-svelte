<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erhe5bc3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erhe5bc3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:screen-desktop" {...props}></Icon>
