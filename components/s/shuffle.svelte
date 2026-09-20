<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0b0racfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k0b0racfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:shuffle" {...props}></Icon>
