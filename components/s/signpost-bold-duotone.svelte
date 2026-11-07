<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8b3tsbxv.css';
import '../../css/e/ets3hjqlz.css';
import '../../css/c/cbsg9jbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8b3tsbxv"/><path class="ets3hjqlz"/><path class="cbsg9jbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-bold-duotone" {...props}></Icon>
