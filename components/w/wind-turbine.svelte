<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiv_i_1yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv_i_1yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wind-turbine" {...props}></Icon>
