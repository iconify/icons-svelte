<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlfvtxb2w.css';
import '../../css/l/lylog5b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tlfvtxb2w"/><path class="lylog5b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrench-20-bold" {...props}></Icon>
