<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bri926yrn.css';
import '../../css/b/b1qs3_bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bri926yrn"/><circle class="b1qs3_bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitesun" {...props}></Icon>
