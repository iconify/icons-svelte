<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0d_yj6xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0d_yj6xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vectary" {...props}></Icon>
