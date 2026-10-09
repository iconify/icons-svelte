<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho_z9ty5t.css';
import '../../css/z/zvwpzebnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ho_z9ty5t"/><path class="zvwpzebnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-forecast-20-bold" {...props}></Icon>
