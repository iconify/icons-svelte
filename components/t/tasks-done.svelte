<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg_c-ubvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg_c-ubvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tasks-done" {...props}></Icon>
