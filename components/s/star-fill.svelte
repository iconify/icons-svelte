<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe_52lb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pe_52lb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:star-fill" {...props}></Icon>
