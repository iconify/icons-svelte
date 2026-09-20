<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn6vp_b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6vp_b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:twenty" {...props}></Icon>
