<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3lgsmb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s3lgsmb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:view-expand-duo" {...props}></Icon>
