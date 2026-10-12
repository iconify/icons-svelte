<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb3pl440z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb3pl440z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:superscript" {...props}></Icon>
