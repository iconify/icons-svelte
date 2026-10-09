<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwbw3abxb.css';
import '../../css/c/c7rkzybvo.css';
import '../../css/h/hberpve6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pwbw3abxb"/><path class="c7rkzybvo"/><path class="hberpve6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safe-48" {...props}></Icon>
