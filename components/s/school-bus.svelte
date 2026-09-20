<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb2406bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zb2406bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:school-bus" {...props}></Icon>
