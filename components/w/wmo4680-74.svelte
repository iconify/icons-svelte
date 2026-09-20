<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbl_ijbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="vbl_ijbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-74" {...props}></Icon>
