<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry-l2ebjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ry-l2ebjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrench-fill-20" {...props}></Icon>
