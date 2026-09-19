<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlakeub9c.css';
import '../../css/c/c_uyv2bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="mlakeub9c"/><path class="c_uyv2bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitesunbehindcloud" {...props}></Icon>
