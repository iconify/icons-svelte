<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsnjdou-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsnjdou-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:search-large" {...props}></Icon>
