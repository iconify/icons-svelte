<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyzqfc13x.css';
import '../../css/e/e_0e-zbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="zyzqfc13x"/><path class="e_0e-zbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:watch" {...props}></Icon>
