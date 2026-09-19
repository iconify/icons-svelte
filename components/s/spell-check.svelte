<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1yp1-b8j.css';
import '../../css/w/w9k2w_r8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w1yp1-b8j"/><path class="w9k2w_r8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:spell-check" {...props}></Icon>
