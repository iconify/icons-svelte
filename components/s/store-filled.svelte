<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxigcqtgr.css';
import '../../css/r/r2mnmqlht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxigcqtgr"/><path class="r2mnmqlht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:store-filled" {...props}></Icon>
