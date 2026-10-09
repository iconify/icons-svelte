<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqlaqcc4h.css';
import '../../css/p/pb5d0bbik.css';
import '../../css/z/zq7fmrmeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqlaqcc4h"/><path class="pb5d0bbik"/><path class="zq7fmrmeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-kit-20" {...props}></Icon>
