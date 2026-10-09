<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud7h_6y6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ud7h_6y6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-forecast-48" {...props}></Icon>
