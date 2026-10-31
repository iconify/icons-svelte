<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_6u2bcnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_6u2bcnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-gloss" {...props}></Icon>
