<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6etv2b0x.css';
import '../../css/q/qy70odgzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v6etv2b0x"/><path class="qy70odgzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruler-20" {...props}></Icon>
