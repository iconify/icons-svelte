<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpd_lfb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cpd_lfb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:vk" {...props}></Icon>
