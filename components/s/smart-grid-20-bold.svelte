<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvggvrfgt.css';
import '../../css/x/x3yktye3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvggvrfgt"/><path class="x3yktye3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-grid-20-bold" {...props}></Icon>
