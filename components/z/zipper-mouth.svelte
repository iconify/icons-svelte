<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bng7pxiak.css';
import '../../css/f/fpr969b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bng7pxiak"/><path class="fpr969b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:zipper-mouth" {...props}></Icon>
