<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbk0qrbla.css';
import '../../css/l/l3azjz_az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbk0qrbla"/><path class="l3azjz_az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:saltcorn-dark" {...props}></Icon>
