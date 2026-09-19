<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs0stz29d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="cs0stz29d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:utensils" {...props}></Icon>
