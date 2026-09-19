<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpifswb1p.css';
import '../../css/c/cuadd06uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fpifswb1p"/><path class="cuadd06uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-color-fill-12" {...props}></Icon>
