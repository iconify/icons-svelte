<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhkk_m-iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhkk_m-iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:toggle-right" {...props}></Icon>
