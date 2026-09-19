<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq1hgyzbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":750};
const content = `<path class="cq1hgyzbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:videocamera" {...props}></Icon>
