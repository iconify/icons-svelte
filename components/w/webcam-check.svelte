<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdt7c6b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdt7c6b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:webcam-check" {...props}></Icon>
