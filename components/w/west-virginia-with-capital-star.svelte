<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsv1ptbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nsv1ptbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:west-virginia-with-capital-star" {...props}></Icon>
