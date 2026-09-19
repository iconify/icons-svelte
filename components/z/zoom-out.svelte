<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2d_nybeh.css';
import '../../css/t/taasc_mln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2d_nybeh"/><path class="taasc_mln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-out" {...props}></Icon>
