<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swzcg5bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swzcg5bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:thumbs-down-sharp" {...props}></Icon>
