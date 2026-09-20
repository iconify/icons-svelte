<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyrcabcak.css';
import '../../css/h/h7o1n1z4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jyrcabcak"/><path class="h7o1n1z4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:speech-bubble-alert-ltr" {...props}></Icon>
