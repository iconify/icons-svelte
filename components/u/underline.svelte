<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_pid-oz.css';
import '../../css/r/r84dxmgyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="r84dxmgyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:underline" {...props}></Icon>
