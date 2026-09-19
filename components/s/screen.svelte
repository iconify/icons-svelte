<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl06_wi1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hl06_wi1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:screen" {...props}></Icon>
