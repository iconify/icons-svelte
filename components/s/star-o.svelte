<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf-r26bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="zf-r26bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:star-o" {...props}></Icon>
