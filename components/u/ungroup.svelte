<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hizocbbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hizocbbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ungroup" {...props}></Icon>
