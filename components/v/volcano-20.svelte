<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2jer4rst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x2jer4rst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volcano-20" {...props}></Icon>
