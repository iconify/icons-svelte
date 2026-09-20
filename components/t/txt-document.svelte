<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egr5ponnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egr5ponnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:txt-document" {...props}></Icon>
