<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/d094f7bjn.css';
import '../../css/f/fbs5khb6z.css';
import '../../css/j/j3akw_70p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d094f7bjn"/><path class="fbs5khb6z"/><path class="j3akw_70p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:train-sharp-two-tone" {...props}></Icon>
