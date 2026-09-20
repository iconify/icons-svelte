<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnbkpb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbnbkpb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-right-box-sharp" {...props}></Icon>
