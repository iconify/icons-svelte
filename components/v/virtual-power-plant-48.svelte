<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-i-fb_p.css';
import '../../css/x/xl9astbne.css';
import '../../css/h/hzypfodab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ya-i-fb_p"/><path class="xl9astbne"/><path class="hzypfodab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:virtual-power-plant-48" {...props}></Icon>
