<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhoe5vyjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhoe5vyjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:telescope-gloss" {...props}></Icon>
