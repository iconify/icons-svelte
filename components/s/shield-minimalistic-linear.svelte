<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djh_z1beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djh_z1beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-linear" {...props}></Icon>
