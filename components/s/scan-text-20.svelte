<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdt8pcsop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdt8pcsop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-text-20" {...props}></Icon>
