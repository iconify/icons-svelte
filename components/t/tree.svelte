<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uywb0kb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uywb0kb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tree" {...props}></Icon>
