<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1r0yixdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1r0yixdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend" {...props}></Icon>
