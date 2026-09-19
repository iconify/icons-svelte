<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws7z_-boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ws7z_-boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:twocolumnsleftalt" {...props}></Icon>
