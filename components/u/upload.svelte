<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu3_v0sqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pu3_v0sqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:upload" {...props}></Icon>
