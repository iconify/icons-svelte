<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txinifb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="txinifb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm-outline" {...props}></Icon>
