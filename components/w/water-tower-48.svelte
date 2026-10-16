<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezpwbhb1t.css';
import '../../css/p/p9mccbcgw.css';
import '../../css/j/jw2qf6buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ezpwbhb1t"/><path class="p9mccbcgw"/><path class="jw2qf6buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-tower-48" {...props}></Icon>
