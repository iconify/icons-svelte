<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsc5iacwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vsc5iacwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:speech-bubbles-ltr" {...props}></Icon>
