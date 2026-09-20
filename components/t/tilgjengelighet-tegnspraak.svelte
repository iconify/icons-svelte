<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa5b_b6dr.css';
import '../../css/r/rvpd67bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa5b_b6dr"/><path class="rvpd67bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:tilgjengelighet-tegnspraak" {...props}></Icon>
