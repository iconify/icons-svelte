<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3tkxm7_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="p3tkxm7_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:surfing" {...props}></Icon>
