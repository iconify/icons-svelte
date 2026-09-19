<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8x56pxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fz8x56pxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:waist-circumference" {...props}></Icon>
