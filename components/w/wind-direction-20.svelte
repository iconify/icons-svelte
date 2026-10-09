<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_rzrek6p.css';
import '../../css/v/vqp7s7b9z.css';
import '../../css/r/rbecf_bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_rzrek6p"/><path class="vqp7s7b9z"/><path class="rbecf_bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-direction-20" {...props}></Icon>
