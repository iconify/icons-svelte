<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmc7_aczv.css';
import '../../css/d/d30tv5bpb.css';
import '../../css/s/ssc_8on_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmc7_aczv"/><path clip-rule="evenodd" class="d30tv5bpb"/><path class="ssc_8on_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:weightlifting-fill" {...props}></Icon>
