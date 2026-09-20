<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0e_vfbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0e_vfbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:spinner-duotone" {...props}></Icon>
