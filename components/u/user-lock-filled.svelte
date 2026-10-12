<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbn2yrbjm.css';
import '../../css/v/v82trt5er.css';
import '../../css/w/wtr3z9boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbn2yrbjm"/><path clip-rule="evenodd" class="v82trt5er"/><path class="wtr3z9boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-lock-filled" {...props}></Icon>
