<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up69iwpxv.css';
import '../../css/o/oyfc2zkqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="up69iwpxv"/><path class="oyfc2zkqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zero-emissions-20" {...props}></Icon>
