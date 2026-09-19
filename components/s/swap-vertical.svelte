<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4_nstbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4_nstbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:swap-vertical" {...props}></Icon>
