<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fph3g9b8f.css';
import '../../css/g/g4fgyobiq.css';
import '../../css/q/q5x211bex.css';
import '../../css/i/ikv4dbcut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fph3g9b8f"/><path class="g4fgyobiq"/><path class="q5x211bex"/><path class="ikv4dbcut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sliders-20-bold" {...props}></Icon>
