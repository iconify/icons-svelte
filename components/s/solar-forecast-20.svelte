<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emwyceb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emwyceb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-forecast-20" {...props}></Icon>
