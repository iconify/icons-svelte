<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un0v2foqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un0v2foqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-variant" {...props}></Icon>
