<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of7srkb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="of7srkb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:temperature-high" {...props}></Icon>
