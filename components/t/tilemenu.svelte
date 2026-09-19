<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5mwqbc4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="j5mwqbc4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tilemenu" {...props}></Icon>
