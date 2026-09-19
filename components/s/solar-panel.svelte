<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma8_qib5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ma8_qib5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:solar-panel" {...props}></Icon>
