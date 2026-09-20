<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2-cmel8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-cmel8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tidal" {...props}></Icon>
