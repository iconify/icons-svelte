<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs9_h7bln.css';
import '../../css/n/ni31jpbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs9_h7bln"/><path class="ni31jpbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:stopwatch-bold" {...props}></Icon>
