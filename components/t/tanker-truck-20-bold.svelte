<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpxwtybmx.css';
import '../../css/n/n9tjabbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mpxwtybmx"/><path class="n9tjabbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tanker-truck-20-bold" {...props}></Icon>
