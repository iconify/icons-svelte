<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3mm8r2qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="x3mm8r2qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ruler-vertical" {...props}></Icon>
