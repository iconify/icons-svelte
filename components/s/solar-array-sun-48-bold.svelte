<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixy5tybnv.css';
import '../../css/s/sypm-h04n.css';
import '../../css/r/rdsgzmbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ixy5tybnv"/><path class="sypm-h04n"/><path class="rdsgzmbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-array-sun-48-bold" {...props}></Icon>
