<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihvpr_l5t.css';
import '../../css/e/e_x4yrbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihvpr_l5t"/><path class="e_x4yrbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-48-bold" {...props}></Icon>
