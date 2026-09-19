<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on18ujy8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="on18ujy8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarel" {...props}></Icon>
