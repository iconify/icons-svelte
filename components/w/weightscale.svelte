<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4_n57b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1023};
const content = `<path class="p4_n57b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:weightscale" {...props}></Icon>
