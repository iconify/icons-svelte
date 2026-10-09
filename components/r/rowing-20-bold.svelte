<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqqbf4jvf.css';
import '../../css/f/flpc-e6db.css';
import '../../css/e/e6txgee1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zqqbf4jvf"/><path class="flpc-e6db"/><path class="e6txgee1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rowing-20-bold" {...props}></Icon>
