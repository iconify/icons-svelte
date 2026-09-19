<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwq_awb_v.css';
import '../../css/i/isfqmkfad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwq_awb_v"/><path class="isfqmkfad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:se-1x1" {...props}></Icon>
