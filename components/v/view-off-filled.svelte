<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi-gm2nxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hi-gm2nxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-off-filled" {...props}></Icon>
