<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9oyev17j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c9oyev17j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shop-lock" {...props}></Icon>
