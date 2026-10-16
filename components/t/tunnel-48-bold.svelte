<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohewcy22n.css';
import '../../css/e/eogp9ogkm.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohewcy22n"/><path class="eogp9ogkm"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tunnel-48-bold" {...props}></Icon>
