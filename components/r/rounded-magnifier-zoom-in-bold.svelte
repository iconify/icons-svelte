<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnj89bbgy.css';
import '../../css/z/z1_dpab3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnj89bbgy"/><path clip-rule="evenodd" class="z1_dpab3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-zoom-in-bold" {...props}></Icon>
