<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mze16cbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mze16cbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sunglasses-sharp" {...props}></Icon>
