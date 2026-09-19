<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsprk2c2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bsprk2c2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:t" {...props}></Icon>
