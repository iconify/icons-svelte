<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l94bcicug.css';
import '../../css/b/bjyphubzh.css';
import '../../css/f/ffcx5ccbi.css';
import '../../css/f/ffv-oibsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l94bcicug"/><path class="bjyphubzh"/><path class="ffcx5ccbi"/><path class="ffv-oibsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-20" {...props}></Icon>
