<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5j-lbxc.css';
import '../../css/m/mo6avcbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ai5j-lbxc"/><path class="mo6avcbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-low-20-bold" {...props}></Icon>
