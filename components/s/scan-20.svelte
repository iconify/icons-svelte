<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrz9qccwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mrz9qccwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-20" {...props}></Icon>
