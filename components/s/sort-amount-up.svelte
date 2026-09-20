<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmp5x0bgg.css';
import '../../css/f/frpv_vbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmp5x0bgg"/><path class="frpv_vbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-amount-up" {...props}></Icon>
