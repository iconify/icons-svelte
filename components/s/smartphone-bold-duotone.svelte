<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4udjm4ma.css';
import '../../css/p/pzq_i-bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4udjm4ma"/><path class="pzq_i-bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-bold-duotone" {...props}></Icon>
