<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2d4ilbfy.css';
import '../../css/s/s86v9c0wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p2d4ilbfy"/><path class="s86v9c0wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:splash-pad" {...props}></Icon>
