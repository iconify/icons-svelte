<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdy7hybaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vdy7hybaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:steam" {...props}></Icon>
