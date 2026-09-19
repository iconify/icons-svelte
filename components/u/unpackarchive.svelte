<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaamf9vwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jaamf9vwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:unpackarchive" {...props}></Icon>
