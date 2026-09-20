<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnpjfhobm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lnpjfhobm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-exclamation-point" {...props}></Icon>
