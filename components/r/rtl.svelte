<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz3sp2bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jz3sp2bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:rtl" {...props}></Icon>
