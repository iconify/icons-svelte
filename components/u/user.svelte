<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s38--pbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s38--pbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user" {...props}></Icon>
