<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfuqf0bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfuqf0bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:webcam-gloss" {...props}></Icon>
