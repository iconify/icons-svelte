<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lllc-r1nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lllc-r1nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:syringe-linear" {...props}></Icon>
