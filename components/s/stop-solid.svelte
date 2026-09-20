<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwigejbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwigejbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:stop-solid" {...props}></Icon>
