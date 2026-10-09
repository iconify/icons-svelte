<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrwbit1kg.css';
import '../../css/l/l_fhzdbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vrwbit1kg"/><path class="l_fhzdbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skyscraper-20-bold" {...props}></Icon>
