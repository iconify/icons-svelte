<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqr-pabak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqr-pabak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:select-all" {...props}></Icon>
