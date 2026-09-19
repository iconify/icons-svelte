<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbk84rbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1472};
const content = `<path class="sbk84rbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sunrise-o" {...props}></Icon>
