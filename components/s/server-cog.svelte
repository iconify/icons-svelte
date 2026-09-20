<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbwtjkb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwtjkb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:server-cog" {...props}></Icon>
