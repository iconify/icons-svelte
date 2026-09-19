<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chbtt6sws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="chbtt6sws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spiderweb" {...props}></Icon>
