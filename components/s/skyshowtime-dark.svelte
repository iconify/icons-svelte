<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzm_x0bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzm_x0bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:skyshowtime-dark" {...props}></Icon>
