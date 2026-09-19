<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t29srkv3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t29srkv3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:unisex-restroom" {...props}></Icon>
