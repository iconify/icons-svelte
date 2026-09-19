<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyp8xxb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zyp8xxb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stockdown" {...props}></Icon>
