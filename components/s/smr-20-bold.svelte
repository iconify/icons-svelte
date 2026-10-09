<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltqeu13ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ltqeu13ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smr-20-bold" {...props}></Icon>
