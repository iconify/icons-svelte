<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_m-zf91d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_m-zf91d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-card-minimalistic-outline" {...props}></Icon>
