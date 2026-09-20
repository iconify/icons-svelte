<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmtf56boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jmtf56boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-outline" {...props}></Icon>
