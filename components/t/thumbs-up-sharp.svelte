<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtg7lpbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtg7lpbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:thumbs-up-sharp" {...props}></Icon>
