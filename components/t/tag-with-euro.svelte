<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9tlc311j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j9tlc311j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-euro" {...props}></Icon>
