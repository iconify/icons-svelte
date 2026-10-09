<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxo9vzbcf.css';
import '../../css/c/ckf78acjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cxo9vzbcf"/><path class="ckf78acjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toaster-20" {...props}></Icon>
