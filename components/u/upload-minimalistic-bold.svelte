<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urermcsco.css';
import '../../css/h/hjvg905kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urermcsco"/><path class="hjvg905kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-minimalistic-bold" {...props}></Icon>
