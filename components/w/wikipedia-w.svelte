<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybhhwn4il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="ybhhwn4il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wikipedia-w" {...props}></Icon>
