<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttj_bebjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttj_bebjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tab-sharp" {...props}></Icon>
