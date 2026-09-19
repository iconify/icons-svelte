<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x03szrc6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x03szrc6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:twocolumnsright" {...props}></Icon>
