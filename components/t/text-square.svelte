<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_pid-oz.css';
import '../../css/c/cy3n3cb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="cy3n3cb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:text-square" {...props}></Icon>
