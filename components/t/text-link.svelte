<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe4vwfu9e.css';
import '../../css/d/d8r3yjb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xe4vwfu9e"/><path class="d8r3yjb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-link" {...props}></Icon>
