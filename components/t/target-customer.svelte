<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgjdvv67z.css';
import '../../css/t/ttm_7fxim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pgjdvv67z"/><path class="ttm_7fxim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:target-customer" {...props}></Icon>
