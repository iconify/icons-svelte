<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1acvi-ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f1acvi-ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:send-right" {...props}></Icon>
