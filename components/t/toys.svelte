<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pji5ilgek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="pji5ilgek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:toys" {...props}></Icon>
