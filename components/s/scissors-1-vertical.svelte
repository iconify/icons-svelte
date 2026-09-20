<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-wkcrisg.css';
import '../../css/u/up737eb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="p-wkcrisg"/><path class="up737eb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:scissors-1-vertical" {...props}></Icon>
