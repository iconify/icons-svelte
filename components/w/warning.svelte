<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sse8e8bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sse8e8bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:warning" {...props}></Icon>
