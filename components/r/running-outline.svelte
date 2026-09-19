<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm04t4mmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fm04t4mmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:running-outline" {...props}></Icon>
