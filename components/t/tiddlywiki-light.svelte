<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j086mhb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j086mhb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tiddlywiki-light" {...props}></Icon>
