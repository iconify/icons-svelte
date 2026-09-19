<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpmo-6vfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fpmo-6vfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sticky-note" {...props}></Icon>
