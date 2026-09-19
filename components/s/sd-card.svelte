<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubpwl-aai.css';
import '../../css/t/tfo27y8rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubpwl-aai"/><path class="tfo27y8rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sd-card" {...props}></Icon>
