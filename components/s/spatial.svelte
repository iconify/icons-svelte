<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkr45ebwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkr45ebwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:spatial" {...props}></Icon>
