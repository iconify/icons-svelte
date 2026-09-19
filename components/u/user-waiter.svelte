<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwq2k-b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1472};
const content = `<path class="rwq2k-b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:user-waiter" {...props}></Icon>
