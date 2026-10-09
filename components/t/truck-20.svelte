<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0dtlbqb.css';
import '../../css/w/w8d7b6b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hm0dtlbqb"/><path class="w8d7b6b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:truck-20" {...props}></Icon>
