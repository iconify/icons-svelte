<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmdu-abxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cmdu-abxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:wheelchair" {...props}></Icon>
