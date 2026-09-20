<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq77w7b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="oq77w7b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thumbs-down" {...props}></Icon>
