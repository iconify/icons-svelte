<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3_liacup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3_liacup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zen-notes-light" {...props}></Icon>
