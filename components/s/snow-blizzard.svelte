<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv7o-5b3h.css';
import '../../css/d/d_h7705bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pv7o-5b3h"/><path class="d_h7705bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:snow-blizzard" {...props}></Icon>
