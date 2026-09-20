<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9x15ko7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x15ko7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:upload-sharp" {...props}></Icon>
