<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou4kbz7is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ou4kbz7is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-75-outline" {...props}></Icon>
