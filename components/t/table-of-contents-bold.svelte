<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw4v4jmms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rw4v4jmms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:table-of-contents-bold" {...props}></Icon>
