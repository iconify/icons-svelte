<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_opybnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w4_opybnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:untappd" {...props}></Icon>
