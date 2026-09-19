<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5p28qgjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r5p28qgjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:vector-square" {...props}></Icon>
