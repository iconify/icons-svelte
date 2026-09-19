<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8pdp68ro.css';
import '../../css/s/swz9s6b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w8pdp68ro"/><path class="swz9s6b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scalpel-cursor" {...props}></Icon>
