<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm94rebtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fm94rebtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:whatsapp" {...props}></Icon>
