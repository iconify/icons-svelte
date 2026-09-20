<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwvo3mbkm.css';
import '../../css/h/h_3msknem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwvo3mbkm"/><path clip-rule="evenodd" class="h_3msknem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:siderbar-bold" {...props}></Icon>
