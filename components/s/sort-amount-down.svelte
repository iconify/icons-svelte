<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i4q55vh.css';
import '../../css/f/frpv_vbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i4q55vh"/><path class="frpv_vbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-amount-down" {...props}></Icon>
