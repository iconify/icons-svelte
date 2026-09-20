<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbf869b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="lbf869b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-8" {...props}></Icon>
