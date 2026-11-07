<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-vry1bva.css';
import '../../css/m/m-4cng7zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-vry1bva"/><path class="m-4cng7zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-card-minimalistic-bold-duotone" {...props}></Icon>
