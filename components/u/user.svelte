<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4eio9bdz.css';
import '../../css/j/j4xpq6z4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4eio9bdz"/><path class="j4xpq6z4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:user" {...props}></Icon>
