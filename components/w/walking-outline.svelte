<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqgck3bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hqgck3bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:walking-outline" {...props}></Icon>
