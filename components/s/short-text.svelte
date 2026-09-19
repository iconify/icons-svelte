<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ux_fb-o.css';
import '../../css/y/y766n9b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ux_fb-o"/><path class="y766n9b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:short-text" {...props}></Icon>
