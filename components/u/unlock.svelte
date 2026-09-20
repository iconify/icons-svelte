<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joehf8bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="joehf8bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:unlock" {...props}></Icon>
