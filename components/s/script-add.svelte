<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3mp59mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eo3mp59mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:script-add" {...props}></Icon>
