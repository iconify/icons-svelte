<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi60hlbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fi60hlbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tree-stump" {...props}></Icon>
