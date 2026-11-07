<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv_i5e0rq.css';
import '../../css/r/rp13nxwka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv_i5e0rq"/><path class="rp13nxwka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tram-bold" {...props}></Icon>
