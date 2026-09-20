<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8ly-hb2i.css';
import '../../css/e/enc01mbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8ly-hb2i"/><path class="enc01mbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subarr" {...props}></Icon>
