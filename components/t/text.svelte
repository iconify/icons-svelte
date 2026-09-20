<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0id9fbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0id9fbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text" {...props}></Icon>
