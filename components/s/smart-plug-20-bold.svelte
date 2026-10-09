<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whf-7i3fs.css';
import '../../css/d/dqs7t3alo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whf-7i3fs"/><path class="dqs7t3alo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-plug-20-bold" {...props}></Icon>
