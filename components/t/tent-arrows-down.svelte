<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw3x82bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="cw3x82bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tent-arrows-down" {...props}></Icon>
