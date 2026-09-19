<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmuj8wb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lmuj8wb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:work" {...props}></Icon>
