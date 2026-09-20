<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1apb5tnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1apb5tnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-justify" {...props}></Icon>
