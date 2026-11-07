<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwtm_3btu.css';
import '../../css/m/mdrgupb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dwtm_3btu"/><path class="mdrgupb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rings-bold-duotone" {...props}></Icon>
