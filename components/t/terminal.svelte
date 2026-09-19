<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_0ix7bza.css';
import '../../css/y/yt0ww0arr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j_0ix7bza"/><path class="yt0ww0arr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:terminal" {...props}></Icon>
