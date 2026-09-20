<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-0aw-32q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r-0aw-32q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:toilet" {...props}></Icon>
