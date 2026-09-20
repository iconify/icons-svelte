<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udgaq9por.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udgaq9por"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sidebar-left2-filled" {...props}></Icon>
