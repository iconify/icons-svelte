<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhyd0pb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zhyd0pb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:twitter-fill" {...props}></Icon>
