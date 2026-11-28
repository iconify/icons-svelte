<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5dvblh_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5dvblh_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sliders-check" {...props}></Icon>
