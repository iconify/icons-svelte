<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kecnv9bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kecnv9bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-charging-gloss" {...props}></Icon>
