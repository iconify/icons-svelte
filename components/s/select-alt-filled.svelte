<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgb8vqb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgb8vqb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:select-alt-filled" {...props}></Icon>
