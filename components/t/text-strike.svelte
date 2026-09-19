<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_pid-oz.css';
import '../../css/r/rj-fah6et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="rj-fah6et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:text-strike" {...props}></Icon>
